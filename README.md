class Solution {
    public boolean isPalindrome(int x) {
  if(x<0)
    		return false;
    	else {
    		String s=x +"";
    		int a= 0;
    		int b=s.length() -1;
    		while(a<b)
    			if(s.charAt(a++) !=s.charAt(b--))
    				return false;
    	}
    	return true;
    }
}

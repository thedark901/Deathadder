# Deathadder
class test2
{ 
    static void String(String str) 
    { 
        StringBuffer  num = new StringBuffer();
          
        for (int i=0; i<str.length(); i++) 
        { 
            if (Character.isDigit(str.charAt(i)))
            {
                num.append(str.charAt(i)); 
            
        } 
            
        }
        
        System.out.println(num); 
        
    } 
      
    
    public static void main(String args[]) 
    { 
    	
        String str = "abc573"; 
        String str2 = "a5b7c3";
        String(str); 
        String(str2); 
       
        
        
    } 
}

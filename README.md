# string-contains-duplicate-letter-or-not

 String a="java";
     String s=a.toLowerCase();
     char[] c=s.toCharArray();
     for(int i=0;i<c.length;i++)
     {
         for(int j=i+1;j<c.length;j++)
         {

             if(c[i]==c[j])
             {
                System.out.println("yes");
                break;
             }
            
         }
     }

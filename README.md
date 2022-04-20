- 👋 Hi, I’m @shabazz3man
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
shabazz3man/shabazz3man is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
public class McGroganArrayMethod
{       
   public static void main(String[]args)
   {
      int[] randomnum = new int[10]; //generating array of 10 elements
      for(int i = 0; i < randomnum.length; i++)
      {
      randomnum[i] = (int)(Math.random() * 49);
      JOptionPane.showMessageDialog(null, randomnum[i]);
           }
      int[]usernum = getUserNum();

   }
   
   public static int[] getUserNum()
   {
      int[]usernum = new int[10];
      for(int i = 0; i < usernum.length; i++){
       JOptionPane.showMessageDialog(null, "Enter in numbers");
      if (usernum < 0 && usernum > 49) 
       {
         JOptionPane.showMessageDialog(null,"invalid");
       }
      else 
      JOptionPane.showMessageDialog(null,"valid");
      }
      return usernum;

   }
    public static void compareArray(int[]arrayA, int[]arrayB)
    {
    for (int i = 0; i < arrayA.length; i++)
    {
    if(arrayB > arrayA){
     JOptionPane.showMessageDialog(null,"The number is less");}
    else
     JOptionPane.showMessageDialog(null,"The number is greater");
     
     System.exit(0);

    }
}   
   
   

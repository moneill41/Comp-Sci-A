# Comp-Sci-A
asd
import java.util.Scanner;

public class sqrtEst
{

   public static double sqrtEst(double a)
   {
      double x = a/2;
      double diff;
   
      do
      {
      diff = x;
      x = (diff + (a/diff))/2;
      }
   
   while ((diff-x)!=0);
   {
   return x;
   }
   }



public static void main(String[] args);

{
Scanner k = new Scanner(System.in);
System.out.println("Enter a number greater than 5.");
double x = k.nextDouble();

System.out.println("" + sqrtEst());




}
}

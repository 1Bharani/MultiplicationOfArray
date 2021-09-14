
package multiplicationofarray;
import java.util.Scanner;
public class MultiplicationOfArray 
{
    
    public static void main(String[] args) 
    {               
     int [] arr = new int [] {1, 2, 3, 4, 5};  
     int mu2 = 1;  
         for (int i = 0; i < arr.length; i++) {  
       mu2 = mu2 * arr[i];  
      }  
       System.out.println("Product of all the elements of an array: " +mu2);  
  }
}   
  

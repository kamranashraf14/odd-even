# odd-even
usser  number is odd or even
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
   
  // if (number % 2 != 0) {
    //        System.out.println(number + " is odd.");
           
            
    if(n%2==0){
      System.out.println("number is even");
    }
    else{
      System.out.println("no");
    }  
    
  }
}

# simple-calculator-
import java.util.*;
public class main{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("enter 1st number:");
        int a = s.nextInt();
        System.out.println("enter 2nd number");
        int b = s.nextInt();
        System.out.println("enter operation to be performed (+ , - , * , / , %)");
        char x = s.next().charAt(0);
    switch (x) {
       case '+' :
      int result = a + b;
       System.out.println("the addition of the two numbers is : " +result);   
       break;
       case '-' :
       result = a - b;
       System.out.println("The subraction of the two numbers is : " +result);
       break;
       case '*' :
       result = a * b;
       System.out.println("The multiplication of the two numbers is : " +result);
       break;
       case '/' :
       result = a / b;
       System.out.println("The divison of the two numbers is : " +result);
       break;
       case '%' :
       result = a % b;
       System.out.println("The modulo of the two numbers is : " +result);
       break;
        default:
        System.out.println("INVALID IMPUTS!!!");
            break;
    }

    }
}  

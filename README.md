import java.util.*;
public class Main{
    public static void main(String args[]){
        Scanner sc=new Scanner (System.in);
        System.out.println(" Enter the number1:-");
        int num1=sc.nextInt();
        System.out.println(" Enter the number2:-");
        int num2=sc.nextInt();
        if(num1>num2)
        {
            System.out.println(num1   +"  Graeter then  "+  num2);
        }
        else if(num1<num2) {
            System.out.println(num2   +"Greater then   "+  num1);
        }
        else{
            System.out.println("Both  the number is is equal");
        }
        
    }
}

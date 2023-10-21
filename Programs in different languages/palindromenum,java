import java.util.Scanner;

public class Palindrome {
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        System.out.println("Enter the number");
        int num=in.nextInt();
        int ans=0;
        int temp=num;
        while(num>0){
            int rem=num%10;
            ans =(ans*10)+rem;
            num/=10;
        }
        if (ans == temp) {
            System.out.println("The number is Palindrome");
        }
        else{
            System.out.println("The number is not Palindrome");
        }
    }
}

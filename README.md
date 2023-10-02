# My-Works-My-Codes
import java.util.*;// print natural numbers from n to 1
public class Recursion1 {
    public void PI(int n){
        if(n==1){
            System.out.println(1);
            return;
        }
        System.out.print(n+" ");
        PI(n-1);
        

    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        Recursion1 o = new Recursion1();
        o.PI(n);
    }
}

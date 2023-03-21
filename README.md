import java.util.Scanner;
public class labprogram26_factorial {
	public static void main(String[] args){
		Scanner s=new Scanner(System.in);
		int i,fact=1,n;
	System.out.print("Enter the number:");
		n=s.nextInt();
		for(i=1;i<=n;i++){
		fact=fact*i;	
		}
	System.out.println("the fibonaci series is:"+fact);
	}
}

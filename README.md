public class Jala {

	public static void main(String[] args) {
		int n=153,a;
		int sum=0;
		int temp;
		temp=n;
		while(n>0)
		{
			a=n%10;
			n=n/10;
			sum=sum +(a*a*a);
		}
		if(sum==temp)
		{
			System.out.println("Given number is Armstrong number");
		}
		
	}
}

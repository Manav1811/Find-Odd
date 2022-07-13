
import java.util.Scanner; 
public class Main 
{

public static void main(String[] args)
 {
	Scanner m = new Scanner(System.in);
	
	long x = m.nextInt();
	long[] y = new long[10];

	
	while(x>0)
	{
		for(int i=0;i<10;i++) 
		{
			y[i] = x % 10;
	
			x = x/10;
	

			if(y[i]%2 != 0)
			{
				System.out.println(y[i]);
			}
		}
	}
 }
}

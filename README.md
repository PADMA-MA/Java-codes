/* to display my name pattern */

import java.util.*;
class name
{
	public static void main(String[] args) 
	{
		Scanner scan=new Scanner(System.in);
		int n=scan.nextInt();
		int i,j,k;
		for(i=0;i<n;i++)
		{
			
for(j=0;j<n;j++)
			{
				if(i==0 && j<n/2 || j==0 || i==n/2 && j<n/2 || j==n/2 && i<n/2 && i!=0)
				{
					System.out.print("P");
				}
					else
				{
						System.out.print(" ");
				}
			}
			for(j=0;j<n;j++)
			{
				if(j==0 && i!=0 || j==n/2 && i!=0 || i==0 && j!=0 && j<n/2 || i==n/2 && j<n/2)
				
				{
					System.out.print("A");
				}
					else
				{
						System.out.print(" ");
				}
			}
			
			for(j=0;j<n;j++)
			{
				if(i==0 && j<n/2 || j==0 || i==n-1 && j<n/2 || j==n/2 && i>0 && i<n-1)
				{
					System.out.print("D");
				}
					else
				{
						System.out.print(" ");
				}
			}
			
			for(j=0;j<n;j++)
			{
				if(j==0 || j==n-1 || i==j && j<=n/2 || i+j==n-1 && i<=n/2)
				{
					System.out.print("M");
				}
					else
				{
						System.out.print(" ");
				}
			}
			for(k=0;k<=3;k++)
			{
				System.out.print(" ");
			}
for(j=0;j<n;j++)
			{
				if(j==0 && i!=0 || j==n/2 && i!=0 || i==0 && j!=0 && j<n/2 || i==n/2 && j<n/2)
				
				{
					System.out.print("A");
				}
					else
				{
						System.out.print(" ");
				}
			}
			System.out.println( );
	}
}
}

# codechef_starters77
Problem
problem code:
Tom and Jerry Chase
soluton:
<code>
#hi poo
import java.util.*;
import java.lang.*;
import java.io.*;
//damo
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		int x,y,t;
		Scanner sc=new Scanner(System.in);
		t=sc.nextInt();
		while(t-->0)
		{
		    x=sc.nextInt();y=sc.nextInt();
		    if(x<y)
		        System.out.println("Yes");
		    else
		        System.out.println("no");
		}
	}
} </code>

Problem Code:
AIRLINES
Solution:
<code>

import java.util.*;
import java.lang.*;
import java.io.*;


class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc=new Scanner(System.in);
		int test=sc.nextInt(),x,y,z;
		for(int i=0;i<test;i++)
		{
		 x=sc.nextInt();y=sc.nextInt();z=sc.nextInt();
		 int tickets=x*10;
		 if(y<tickets)
		    System.out.println(y*z);
		 else
		    System.out.println(tickets*z);
		}
	}
}

	</code>
Problem Code:
TEKKEN
Solution:
 <code>
import java.util.*;
import java.lang.*;
import java.io.*;


class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc=new Scanner(System.in);
		int test=sc.nextInt(),a,b,c;
		for(int i=0;i<test;i++)
		{
		    a=sc.nextInt();b=sc.nextInt();c=sc.nextInt();
		    if(b>c)
		    a=a-(b-c);
		    else a=a-(c-b);
		    if(a>0)
		        System.out.println("yes");
		    else
		        System.out.println("no");
		    
		}
	}
}

</code>

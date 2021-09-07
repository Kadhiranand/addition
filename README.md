import java.util.Scanner;
public class BiggestNumber
{
public static void main(String[] args)
{
int num1, num2, num3;
Scanner s = new Scanner(System.in);
System.out.print(&quot;Enter the first number:&quot;);
num1 = s.nextInt();
System.out.print(&quot;Enter the second number:&quot;);
num2 = s.nextInt();
System.out.print(&quot;Enter the third number:&quot;);
num3 = s.nextInt();
if(num1 &gt; num2 &amp;&amp; num1 &gt; num3)
{
System.out.println(&quot;Largest number is:&quot;+num1);
}
else if(num2 &gt; num1 &amp;&amp; num2&gt;num3)
{
System.out.println(&quot;Largest number is:&quot;+num2);
}
else
{
System.out.println(&quot;Largest number is:&quot;+num3);
}
}
}

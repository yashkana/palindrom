# palindrom<br>
using System;<br>
public class palindromexample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n, r, sum = 0, temp;<br>
        Console.Write("enter the number:");<br>
        n = int.Parse(Console.ReadLine());<br>
        temp = n;<br>
        while (n > 0)<br>
        {<br>
            r = n % 10;<br>
            sum = (sum * 10) + r;<br>
            n = n / 10;<br>
        }<br>
        if (temp == sum)<br>
            Console.Write("number is palindrom");<br>
        else
           Console.Write ("number is not palindrom");<br>
    }<br>
}<br>

OUTPUT
![Screenshot 2022-03-04 101204](https://user-images.githubusercontent.com/98301023/156700819-2e841675-1541-4d27-8974-69d4828b3d9e.png)


ARMSTRONG NUMBER EXAMPLE<br>
using System;<br>
public class ArmstrongExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n, r, sum = 0,temp;<br>
        Console.Write("enter the number:");<br>
        n = int.Parse(Console.ReadLine());<br>
        temp = n;<br>
        while(n>0)<br>
        {<br>
            r = n % 10;<br>
            sum = sum + (r * r * r);<br>
            n = n / 10;<br>
        }<br>
        if (temp == sum)<br>
            Console.Write("Armstrong Number");<br>
        else<br>
            Console.Write("not Armstrong number");<br>
    }<br>
}<br>

OUTPUT
![Screenshot 2022-03-04 101747](https://user-images.githubusercontent.com/98301023/156701237-5b94b0a6-0595-4fec-b6cf-b77a4dd09443.png)<br>

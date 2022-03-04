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



WITE A PROGRAM TO FACTORIAL OF NUMBER<br>
using System;<br>

public class factorialexample<br>
{<br>
    class Program<br>
    {<br>
      public  static void Main(string[] args)<br>
        {<br>
            int i, fact = 1, number;<br>
            Console.Write("enter any number:");<br>
            number = int.Parse(Console.ReadLine());<br>
            for(i=1;i<=number;i++)<br>
            {<br>
                fact = fact * i;<br>
            }<br>
            Console.Write("Factorial of " + number + " is  " + fact);<br>
        }<br>
    }<br>
}<br>

OUTPUT:
![Screenshot 2022-03-04 102202](https://user-images.githubusercontent.com/98301023/156701634-da4a9cd9-09c8-4fd4-a9ff-a86d2cf302b8.png)



WRIT PROGRAM TO FIBONACCI series<br>
using System;<br>

namespace fibonaci<br>
{
    public class Program<br>
    {<br>
       public static void Main(string[] args)<br>
        {<br>
            int n1 = 0, n2 = 1, n3, i, number;<br>
            Console.Write("enter the number of elements:");<br>
            number = int.Parse(Console.ReadLine());<br>
            for(i=2;i<number;i++)<br>
            {<br>
                n3 = n1 + n2;<br>
                Console.Write(n3 + " ");<br>
                n1 = n2;<br>
                n2 = n3;<br>
            }<br>
        }<br>
    }<br>
}<br>

OUTPUT
![Screenshot 2022-03-04 103104](https://user-images.githubusercontent.com/98301023/156702617-0d0e1cd2-50a7-486c-b70a-ac8b113dcd92.png)



prime number
using System;<br>
public class PrimenumberExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n, i, m = 0, flag = 0;<br>
        Console.Write("enter the number to check prime:");<br>
        n = int.Parse(Console.ReadLine());<br>
        m = n / 2;<br>
        for(i=2;i<=m;i++)<br>
        {<br>
            if(n%i==0)<br>
            {<br>
                Console.Write("Number is not prime:");<br>
                flag = 1;<br>
                break;<br>
            }<br>
        }<br>
        if (flag == 0)<br>
          Console.Write("Number is  prime:");<br>
    }<br>
            output:
![Screenshot 2022-03-04 104414](https://user-images.githubusercontent.com/98301023/156703667-5f4fd1cd-0fc4-447e-894e-f7b6b8936a0f.png)





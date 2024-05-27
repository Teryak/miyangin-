```c#
namespace soosis
{
    internal class Program
    {
        static void Main(string[] args)
        {

            int firstnum,secnum;

            Console.WriteLine("enter your first num");
            firstnum = int.Parse(Console.ReadLine());
            Console.WriteLine("enter your second num");
            secnum = int.Parse(Console.ReadLine());
               int num = (firstnum + secnum) / 2;

            if (firstnum > num)
                Console.WriteLine("Hello");
            else
              Console.WriteLine("Bay");

            Console.ReadKey();
 
        }
    }
}
```

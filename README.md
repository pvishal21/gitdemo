
namespace ConsoleApp2
{
        // SUM OF N NATURAL NUMBERS
    internal class Class10
    {
        static void Main(string[] args)
        {
            int n, i = 1, sum = 0;

                Console.Write("Enter n value :");
                 n = int.Parse(Console.ReadLine());

            while(i<=n)
            {
                Console.Write(i+"\t");
                sum=sum+i;
                i++;
            }

            Console.WriteLine("\n sum of {0} number is {1}",n,sum);    

        }

    }
}

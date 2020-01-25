# foss1


WAP in c# to show the use of  while loop



using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication17
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = 1;
            while (n <= 10)
            {
                if (n % 2 == 0)
                {
                    n++;
                }
                else
                {
                    Console.Write(" " + n);
                    n++;
                }
            }
            Console.ReadKey();

        }
    }
}















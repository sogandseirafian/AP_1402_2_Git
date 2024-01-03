# AP_1402_2_Git
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_2.CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //برنامه ای بنویسد که آرایه با سایز د وارد و خانه های برابر 7 بنویسد
            int n = Convert.ToInt32(Console.ReadLine());
            int Counter = 0;
            int[] arr = new int[n];
            for (int i = 0; i < n; i++)
            {
                arr[i] = Convert.ToInt32(Console.ReadLine());
                if (arr[i] == 7)
                {
                    Counter++;

                }

            }
            Console.WriteLine(Counter);
        }
    }
}

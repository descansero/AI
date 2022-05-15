using System;
using System.Diagnostics;

namespace ConsoleApp2
{
    class Program
    {
        static void Main(string[] args)
        {

           
            long pos2 = 0;
            while (pos2 < 100000000010000000)
            {
                var random = new Random();
                pos2 = pos2 + random.Next(0, 9);
                if (pos2 < 10)
                {
                    string pos3 = (pos2.ToString());
                    pos3 = "00" + pos2;
                    Console.WriteLine(pos3);
                }
                else if (pos2 < 100)
                {
                    string pos3 = (pos2.ToString());
                    pos3 = "0" + pos2;
                    Console.WriteLine(pos3);
                }
                else if (pos2 < 1000)
                {
                    
                    string pos3 = (pos2.ToString());
                    pos3 = "0" + pos2;
                    Console.WriteLine(pos3);
                }
                else
                {
                    Console.WriteLine(pos2.ToString());
                }
                if (pos2 == 073 && pos2 == 0223 && pos2 == 4974028506313043)
                {
                    Console.WriteLine("acertado");
                    pos2 = 10000000000000000;
                }
                
            }



        }
    }
}





        

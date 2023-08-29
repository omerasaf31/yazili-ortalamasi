# yazili-ortalamasi
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /*
            0-45: F Kaldınız
            45-55: D Geçtiniz
            55-65 : C Geçtiniz.
            75-65:   B Geçtiniz
            75-100:   A Geçtiniz
             
             */


            double yazili1 = 25;
            double yazili2 = 45;
            double yazili3 = 85;
            double ortalama = (yazili1 + yazili2 + yazili3) / 3;
            if (ortalama <45)
            {
                Console.WriteLine("kaldiniz"); 
                
            }
            if (ortalama >= 45 && ortalama<55)
            {
                Console.WriteLine("D Geçtiniz");

            }
            if (ortalama >= 55 && ortalama<65)
            {
                Console.WriteLine("C Geçtiniz");

            }
            if (ortalama >= 65 && ortalama < 65)
            {
                Console.WriteLine("B Geçtiniz");

            }
            if (ortalama >= 75 && ortalama < 100)
            {
                Console.WriteLine("A Geçtiniz");

            }

            Console.ReadKey();


        }


    }
}

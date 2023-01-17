# C-
Ogrenci Bilgi Sistemi

using System;

namespace Degiskenler

{
    class Program
    {
        static void Main(string[] args)
        {
            string ad, soyad, bolum, ders;
            int s1, s2, s3, ort;

            //String degiskenlerin atamaları
            ad = "Zeynep";
            soyad = "Atceken";
            bolum = "Bilgisayar Muhendisligi";
            ders = "Sayısal analiz";

            //Int degiskenlerin atamaları
            s1 = 65;
            s2 = 72;
            s3 = 94;
            ort = (s1 + s2 + s3) / 3;

            //Yazdırma komutları
            Console.WriteLine("***** Ogrenci Bilgi Sistemi *****");
            Console.WriteLine();
            Console.WriteLine("Ogrenci Adı Soyadı :" + ad + " " + soyad);
            Console.WriteLine("Bolum :" + bolum);
            Console.WriteLine("Ders :" + ders);
            Console.WriteLine("Ortalama :" + ort);
            Console.Read();

    }
}
}

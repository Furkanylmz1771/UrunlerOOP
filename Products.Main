using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ÜRÜNLER
{
    public class Program
    {
        static void Main(string[] args)
        {

            Ürünler UrunItem = new Ürünler();


            UrunItem.UrunAdı = "Cips";
            UrunItem.UrunStoğu = 20;
            UrunItem.UrunFiyatı = 5m;
            UrunItem.UrunBoyutu = 5;


            Ürünler UrunItem2 = new Ürünler();

            UrunItem2.UrunAdı = "Çikolata";
            UrunItem2.UrunStoğu = 50;
            UrunItem2.UrunFiyatı = 3m;
            UrunItem2.UrunBoyutu = 3;


            Ürünler UrunItem3 = new Ürünler();

            UrunItem3.UrunAdı = "Su";
            UrunItem3.UrunStoğu = 100;
            UrunItem3.UrunFiyatı = 3m;
            UrunItem3.UrunBoyutu = 4;


            Ürünler[] UrunDizisi = new Ürünler[]               // Dizi oluşturuldu     UrunDizisi istendiğinde
                                                               // UrunItem     UrunItem2  UrunItem3 getirilir.

            {
                UrunItem,
                UrunItem2,
                UrunItem3
             };


            foreach (Ürünler item in UrunDizisi)
            {
                ListBox1.Items.AddRange(UrunDizisi);        // Dizinin tamamını ekler.  ListBox'ta, Items Özelliğini kullanarak ListBox'a öğeler ekleyebilirsiniz.
                                                            // Bu özellik, şu anda ListBox'ta depolanan öğelerin listesine bir başvuru almanıza olanak tanır.
            };






            Satıcılar Satıcı = new Satıcılar();

            Satıcı.Adı = "Ahmet";
            Satıcı.Tecrübesi = 4;
            Satıcı.SatışYeri = "İstanbul";
            Satıcı.Yası = 34;


            Satıcılar Satıcı2 = new Satıcılar();

            Satıcı.Adı = "Selim";
            Satıcı.Tecrübesi = 17;
            Satıcı.SatışYeri = "Adana";
            Satıcı.Yası = 45;



            Satıcılar[] SatıcıDizisi = new Satıcılar[]                         // Dizi oluşturuldu     UrunDizisi istendiğinde
                                                                                                      // UrunItem   UrunItem2  UrunItem3 getirilir.
                                                                                                                 
            {
               Satıcı,
               Satıcı2
            };


            foreach (Satıcılar item in SatıcıDizisi)
            {
                ListBox1.Items.AddRange(SatıcıDizisi);

            };



        }
    }
}

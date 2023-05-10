- INTERFACE KODU:

isim örnek olarak IPersonellerService

void Add(tabloİsmi1 nesneİsmi1 );


- CLASS KODU:

isim örnek olarak PersonellerManager

önce interface'yi implament ediyoruz ardından şu kodları yazıyoruz;

   

        RentACarOtomasyonuEntities1 RentACar = new RentACarOtomasyonuEntities1();

        public void Add(personeller personel)
        {
            RentACar.Set<personeller>().Add(personel);
            RentACar.SaveChanges();
        }
    
        

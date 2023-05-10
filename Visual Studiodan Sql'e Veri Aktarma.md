- INTERFACE KODU:

isim örnek olarak IPersonellerService

void Add(tabloİsmi1 nesneİsmi1);


- CLASS KODU:

isim örnek olarak PersonellerManager

önce interface'yi implament ediyoruz ardından şu kodları yazıyoruz;

   

        VeriTabanıİsmiEntity nesneİsmi2 = new VeriTabanıİsmiEntity;

        public void Add(tabloİsmi1 nesneİsmi1)
        {
            nesneİsmi2.Set<tabloİsmi1>().Add(nesneİsmi1);
            nesneİsmi2.SaveChanges();
        }
    
        

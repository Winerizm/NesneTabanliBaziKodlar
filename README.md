#10.05.23 Hocanın verdiği kodlar;

- LİSTELEME:

gridControl1.DataSource=(FROM X GORÜSMELER 

SELECT NEW 

{

// alan İSİMLERİ

}).toList();


- TANIMLAMA:
Load:
 rh.Bolumler.Load();
 
bindingSource1.DataSource=rc.Blumler.Local;


 gridView1_CellValueChanged:
try içine: rh.SaveChanges();

catch içine: (message box yarısı)

- Fazladan açılmasını engelleme
GorusmeListesi gorusmeListesi;

if(gorusmeListesi==null||gorusmeListesi.IsDisposed)

{

gorusmeListesi= new GorusmeListesi();

gorusmeListesi.MdiParent=this;

gorusmeListesi.Show

}


# InternetBanking

Proje temel bir internet bankacılığı sitesidir.(şimdilik tek kullanıcı olarak tasarlanmıştır, geliştirilebilir.)

ANA SAYFA ;


database deki kullanıcıya ait hesapların listelendiği ana sayfadır.

oklara basılarak kullanıcıya ait diğer hesap bilgileri görüntülenmektedir.

sayfada iki çıkış butonu mevcuttur.

diğer hizmetlere geçiş için solda sabit menü vardır.



![image](https://user-images.githubusercontent.com/94555987/180976015-a2240efd-d726-407b-9350-b996a8e410af.png)


 
 DİĞER HESAP BİLGİLERİNİN GÖRÜNTÜSÜ;
 

![image](https://user-images.githubusercontent.com/94555987/180977261-fd65ac46-0925-447b-976e-557a52655827.png)



DÖVİZ KURU SAYFASI



listeleye basıldığında girilen verilere göre o tarihin kur değerini  bulup ekrana göstermektedir.

 database deki currency_equivalent tablosundaki mevcut değerler içinde arama yapmaktadır.
 
 
 
 ![image](https://user-images.githubusercontent.com/94555987/180986322-176d6fc6-0198-47a2-a5e8-445ca81973ab.png)

 
 
  DÖVİZ ALIM SAYFASI 
  
  
  ![image](https://user-images.githubusercontent.com/94555987/180984304-43abf575-5f20-4fdb-8c9f-8e4184368bd7.png)



 üstte tl hesaplarının adı listelenir.
 
 döviz alım sayfası seçilen tl hesabından girilen değerlere göre alım yapmaktadır.
 
 account_activities tablosu her hesabın son hareketlerini göstermektedir. döviz alımdan sonra güncellenmektedir.
 
 bakiyeler alımdan sonra güncellenir.
 
 girilen para miktarı hesabın bakiyesini aşmayacak şekilde kontrolü yapılmaktadır yanlış değerlerde uyarı mesajı verilmektedir.
 
  döviz alımı gerçekleştiğinde işlem başarılı ekranı dönmektedir.
  
  
 ![image](https://user-images.githubusercontent.com/94555987/180984162-a277d118-0966-4ec3-aa2e-29b670bceda4.png)
 
 

 
 DÖVİZ SATIM SAYFASI
 
 
 
 bu ekranda seçilen döviz hesabından girilen miktar satılmaktadır ve bakiyeden bu miktar düşürülmektedir.
 
 uygun değer girilmezse uyarı mesajı döndürülür.
 
 işlem gerçekleştiğinde işlem başarılı ekranı döndürülür. 
 
 
 
 HESAP OLUŞTURMA SAYFASI
 
 
  account table'a yeni veri eklenir.
  
 işlem gerçekleştiğinde işlem başarılı ekranı döndürülür.
 
 
![image](https://user-images.githubusercontent.com/94555987/180985069-50ed2df4-9c1b-4abf-961e-f86659b1e703.png)




DÖVİZ TÜRÜ EKLEME SAYFASI


currency table güncellenir.

 işlem gerçekleştiğinde işlem başarılı ekranı döndürülür.
 
 
 
![image](https://user-images.githubusercontent.com/94555987/180985618-b21d9c55-058b-4e36-a157-d4594c2a0786.png)



DÖVİZ KURU TANIMLAMA SAYFASI


currency_equivalent tablosuna veri ekleme yapılır.


 işlem gerçekleştiğinde işlem başarılı ekranı döndürülür.
 
 
 
![image](https://user-images.githubusercontent.com/94555987/180985839-dacff38a-6977-4669-a1e2-9a607f19ed56.png)




 

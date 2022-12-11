# ehir tablosu ile ülke tablosunda bulunan şehir (şehir) ve ülke (ülke) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu kaldırabilirsiniz.
müşteri tablosu ile ödeme tablosunda bulunan ödeme_id ile müşteri tablosundaki ad ve soyad isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yürüttüğünüz.
müşteri tablosu ile kiralama tablosunda bulunan rent_id ile müşteri tablosundaki ad_ad ve soyad isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yürüttüğünüz.

 şehir SEÇİN . isim , ülke . ad  Şehirden SOL KATILIN ülke AÇIK  şehir . kimlik = ülke _ şehir_id ;

 ödemeyi SEÇİN . ödeme_kimliği , müşteri . ad , müşteri . last_name  ödemeden itibaren Müşteriye SAĞDAN KATILIN ödeme ÜZERİNE  . ödeme_kimliği = müşteri . ödeme_id ;

 müşteri SEÇİN . ad , müşteri . soyadı , kiralık . Rental_id   müşteriden FULL JOIN kiralama müşterisine  . _ rent_id = kiralama . kiralama_id ;

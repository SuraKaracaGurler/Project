Müşteri Deneyimi Veri Analizi Raporu
Veri Seti Yapısı ve Genel Bilgi
Analiz kapsamında kullanılan veri seti, 1000 müşteriye ait 14 değişken içermektedir. 
Değişkenler arasında hem sayısal (yaş, site üzerinde geçirilen zaman, satın alınan ürün sayısı vb.) hem de kategorik 
(cinsiyet, konum, müşteri tutundurma durumu) veriler bulunmaktadır.
Hedef değişken olarak “Retention_Status” (müşteri tutundurma durumu) kullanılmış ve bu değişken hem kategorik hem sayısal 
olarak modellenmeye uygundur.

Veri Kalitesi ve Eksik Değerler
Veri setinde eksik veri bulunmamaktadır.
Bu durum, veri kalitesinin yüksek olduğunu ve ön işleme aşamasında ek doldurma veya veri silme gibi işlemlere 
gerek kalmadığını göstermektedir.
Ayrıca, tüm sayısal değişkenlerde aykırı değer kontrolü yapılmış ve herhangi bir aykırı veri tespit edilmemiştir.
Bu, veri setinin tutarlı ve güvenilir olduğunu teyit eder.

Hedef Değişkenin Dağılımı ve Sınıf Dengesi
Müşteri tutundurma durumu incelendiğinde, 694 müşteri (%69.4) “Retained” (kalıcı) olarak sınıflandırılırken, 
306 müşteri (%30.6) “Churned” (kaybedilen) olarak yer almaktadır.
Sınıflar arasında göreceli bir denge bulunmakla beraber, modelleme aşamasında dengeleyici yöntemler değerlendirilmelidir.

Kategorik Değişkenlerin Dağılımı ve Hedef İlişkisi
Cinsiyet dağılımında erkekler %52.4, kadınlar %47.6 oranında temsil edilmektedir.
 Konuma göre dağılım ise kentsel, banliyö ve kırsal alanlarda neredeyse eşit dağılmıştır.
 Hedef değişken ile ilişkili olarak, erkek müşterilerin ortalama tutundurma oranı (%70.2), kadınlara (%68.5) kıyasla biraz daha yüksektir.
 Bölgesel olarak banliyö (%73.0) ve kırsal (%71.2) bölgelerde müşteri tutundurma oranları kentsel bölgeye (%64.2) göre daha iyidir.

Korelasyon Analizi
Korelasyon değerleri -1 ile +1 arasında olup, 0'a yakın değerler zayıf ilişkiyi ifade eder.
Bu durumda Retention_Status_Encoded ile analiz edilen değişkenler arasında anlamlı veya güçlü bir doğrusal ilişki bulunmamaktadır.
Bu değişkenlerin müşteri tutundurma üzerinde doğrudan, güçlü bir etkisi olmadığı görülmektedir. 

Sayısal Değişkenlerin Dağılımı ve İncelemesi
Sayısal değişkenlerin histogram ve kutu grafikleri ile dağılımı incelenmiş, verilerin genel olarak normal dağılıma uygun olduğu
 ve aykırı değer içermediği doğrulanmıştır.
 Müşterilerin site üzerinde geçirdiği zaman, ürün satın alma ve ürün görüntüleme sayıları gibi metrikler, müşteri tutundurma durumu
 ile ilişkili olarak analiz edilmiş ve modelleme için uygunluk gösterdiği gözlemlenmiştir

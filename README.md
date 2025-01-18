CICIDS2017 veri kümesi üzerinde makine öğrenmesi algoritmaları kullanılarak bilgisayar ağlarında anomali tespitine yönelik bir proje geliştirilmiştir. 
Proje, aşağıdaki adımlardan oluşmaktadır. 

1.	Ön işleme (Preprocessing): Ağ trafiği verilerinin temizlenmesi, eksik verilerin işlenmesi ve analiz için uygun hale getirilmesi.
2.	İstatistiksel Analiz (Statistics): Ağ trafiği verilerindeki normal ve anormal davranışların genel desenlerinin ortaya konulması.
3.	Saldırı Filtreleme (Attack Filter): Bilinen saldırıların ağ verilerinden ayrıştırılması ve saldırı örüntülerinin belirlenmesi.
4.	Özellik Seçimi (Feature Selection): Verilerin boyutunu azaltarak en anlamlı ve etkili özelliklerin belirlenmesi.
5.	Makine Öğrenimi Uygulaması: Seçilen özellikler üzerinden makine öğrenmesi algoritmalarının eğitilmesi ve test edilmesi.
6.	Sonuçların Değerlendirilmesi: Önerilen yöntemin doğruluk, hassasiyet ve verimlilik açısından performansının değerlendirilmesi.


Bu çalışmada kullanılan veri seti: CICIDS2017 

Projeyi çalıştırmak için bu veri setinin indirilip VeriSeti klasöründe tutulması gerekmektedir. VeriSeti klasörü ile proje aynı dizinde bulunmalıdır.

Bu çalışmada kullanılan makine öğrenme algoritmaları: Random Forest, MLP, En Yakın Komşu Algoritması (k-nn), Naive Bayes, ID3

Bu çalışmada kullanılan performans ölçütleri: Doğruluk(Accuracy), Kesinlik(Precision), Duyarlılık(Recall), F1-score 


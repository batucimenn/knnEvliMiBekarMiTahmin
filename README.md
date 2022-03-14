# Medeni Hal Tahmini

Bu çalışma Jupyter Notebook üzerinde Python dili kullanılarak yapılmıştır ve Kaggle'da bulunan [“A Credit Card Dataset for Machine Learning"](https://www.kaggle.com/rikdifos/credit-card-approval-prediction) veri seti kullanılmıştır.

438557 satırdan oluşan veri düzenlenerek 5000 satıra düşürülmüştür. Temel sebebi K - En Yakın Komşu Algoritması (KNN) uygulandığında algoritma başarımı %78 olmasına rağmen evli, bekar oranındaki dağılımın dengesiz olması ve makine tahminin sürekli olarak evli sonucuna ulaşmasıdır. Düzenlenmiş verinin algoritma başarımı %86 olarak elde edilmiştir. 

## K - En Yakın Komşu Algoritması (KNN)

K - En Yakın Komşu Algoritması sınıf niteliği belli olan elemanların meydana getirdiği uzaya yeni bir örnek yani sınıf niteliği belli olmayan eleman eklendiğinde bu örneğin kendisine en yakın olan sınıfa dahil edilmesi gerektiğini kararlaştıran bir algoritmadır. Veri kümesinde dengesizlik olduğunda başarı oranı düşer. Kendisine en yakın olan sınıfı belirlemek için bir k değişkeni kullanmaktadır. Çalışmada en yakın 5 komşuya göre sınıflandırma yapılmıştır.

### 1. Ana Pencere
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/anaPencere.JPG)
### 2. Evli Tahmini
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/evli.JPG)
### 3. Bekar Tahmini
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/bekar.JPG)
### 4. Algoritma Başarımı
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/basarimPenceresi.JPG)
### 5. Evli Bekar Oranı
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/evliBekarOranlari.JPG)
### 6. Veri Seti Penceresi
![medeniHalTahminiKNN](https://github.com/batucimenn/medeniHalTahminiKNN/blob/main/ekranGoruntuleri/veriSetiPenceresi.JPG)

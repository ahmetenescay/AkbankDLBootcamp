##Akbank Derin Öğrenme Sınıflandırma Projesi
#Bu proje, Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiş bir derin öğrenme sınıflandırma projesidir. Projenin amacı, Kaggle üzerinde bulunan büyük ölçekli bir balık veri setini kullanarak bir derin öğrenme modeli eğitmek ve sınıflandırma yapmak.

#Proje Hakkında
Balık türlerini sınıflandırmak amacıyla derin öğrenme modelleri kullanılarak veri analizi ve modelleme yapılmıştır. Bu projede, Kaggle'daki balık veri seti kullanılmıştır. Proje süresince veri ön işleme, model eğitimi ve model değerlendirme aşamaları gerçekleştirilmiştir.

##Veri Seti: Large Scale Fish Dataset
#Proje İçeriği
Veri Ön İşleme: Veri seti, klasörler halinde organize edilmiş balık görüntülerinden oluşmaktadır. Veri işleme aşamasında bu görseller uygun bir formata dönüştürülmüş ve Pandas DataFrame yapısına benzer bir veri yapısı elde edilmiştir.

#Görsellerin yüklenmesi
#Veri setinin görselleştirilmesi
#Eğitim ve test setlerine ayrılması
#Modelin Eğitilmesi: Derin öğrenme modeli olarak bir Yapay Sinir Ağı (ANN) mimarisi kullanılmıştır. Modelin katman sayısı, düğüm sayısı, aktivasyon fonksiyonları ve dropout oranı gibi parametreler optimize edilmiştir.

#TensorFlow/Keras kütüphanesi ile model oluşturulması
#Modelin katman yapısı ve hiperparametreler ile oynanarak optimizasyon yapılması
#Modelin Değerlendirilmesi: Eğitim sırasında modelin başarımı değerlendirilmiş, accuracy ve kayıp fonksiyonu (loss) metrikleri hesaplanmıştır. Ayrıca confusion matrix ve classification report kullanılarak daha ayrıntılı bir değerlendirme yapılmıştır.

#Hiperparametre Optimizasyonu: Modelin performansını artırmak için çeşitli hiperparametreler üzerinde denemeler yapılmıştır.

#Katman sayısı, düğüm sayısı, optimizer seçimi gibi parametrelerle oynanmıştır.
#Overfitting kontrolü sağlanmıştır.
##Kullanılan Kütüphaneler
#TensorFlow / Keras
#Pandas
#NumPy
#Matplotlib
#Scikit-learn
##Kurulum
#Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

Kaggle Notebook Ortamında projeyi çalıştırabilirsiniz. Projeyi Kaggle üzerinde çalıştırmak, veri setinin büyük boyutu nedeniyle tavsiye edilir.

##Proje Linki
https://www.kaggle.com/code/ahmetenesay/akbank-derin-renme-s-n-fland-rma-projesi


##Proje Adımları
#Veri Ön İşleme:

##Veri setindeki görüntülerin yüklenmesi ve sınıflandırmaya uygun hale getirilmesi
#Eğitim ve test setlerinin oluşturulması
#Modelin Eğitilmesi:

##Yapay sinir ağı mimarisinin kurulması ve eğitilmesi
#Model Değerlendirilmesi:

##Accuracy ve loss grafikleri ile modelin değerlendirilmesi
#Confusion matrix ve classification report ile model performansının analiz edilmesi
#Hiperparametre Optimizasyonu:

#Katman sayısı, düğüm sayısı, dropout oranı gibi parametreler optimize edilmiştir.
##Sonuçlar
#Model, balık türlerini yüksek doğruluk oranıyla sınıflandırmayı başarmıştır. Proje boyunca overfitting engellenmiş ve modelin genel başarısı artırılmıştır.


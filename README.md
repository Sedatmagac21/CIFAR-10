CIFAR-10 Görüntü Sınıflandırma Projesi
Projenin Amacı

Bu proje, derin öğrenme teknikleri kullanarak CIFAR-10 veri setindeki 10 farklı nesne sınıfını (uçak, otomobil, kuş, kedi, köpek, gemi, kurbağa, at, gemi, kamyon) doğru bir şekilde sınıflandırmayı hedeflemektedir. Evrişimli sinir ağları (CNN) mimarisi ile geliştirilen model, 32x32 piksel boyutundaki renkli görüntüleri analiz ederek doğru sınıfı tahmin eder.

Kullanılan Teknolojiler

Python: Projenin ana programlama dili.
TensorFlow & Keras: Derin öğrenme modelinin oluşturulması, eğitimi ve değerlendirilmesi için kullanılmıştır.
scikit-learn: Model performansının değerlendirilmesi için F1 skoru ve sınıflandırma raporu gibi metriklerin hesaplanmasında kullanılmıştır.
NumPy: Veri manipülasyonu ve matematiksel işlemler için.
Matplotlib: Eğitim sonuçlarının görselleştirilmesi için (opsiyonel).
Veri Seti

CIFAR-10 veri seti, 60.000 adet 32x32 piksel boyutunda renkli görüntüden oluşur. Bu görüntüler 10 farklı nesne sınıfına ayrılmıştır. Veri seti, modelin eğitimi için 50.000, test edilmesi için ise 10.000 görüntü içerir.

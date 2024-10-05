CIFAR-10 Görüntü Sınıflandırma Projesi
Proje Amacı
Bu proje, CIFAR-10 veri seti kullanılarak bir görüntü sınıflandırma modeli geliştirmeyi amaçlamaktadır. CIFAR-10 veri seti, 32x32 boyutunda 60.000 renkli görüntü içerir ve 10 sınıfa ayrılmıştır (uçak, otomobil, kuş, kedi, köpek, gemi gibi). Amaç, evrişimsel sinir ağları (CNN) kullanarak bu görüntülerin doğru sınıflandırılmasını sağlamaktır.

Kullanılan Teknolojiler ve Kütüphaneler
Python: Genel programlama dili.
TensorFlow & Keras: Modelin oluşturulması, eğitimi ve değerlendirilmesi için kullanılan yüksek seviyeli derin öğrenme kütüphaneleri.
scikit-learn: Model değerlendirmesi için F1 skoru ve sınıflandırma raporu alınmasında kullanıldı.
Numpy: Verilerin işlenmesi ve matematiksel işlemler için.
Matplotlib: Eğitim sonuçlarını görselleştirmek için (isteğe bağlı).
Veri Seti
CIFAR-10 veri seti, aşağıdaki 10 sınıfa ait 60.000 görüntüden oluşur:

Uçak
Otomobil
Kuş
Kedi
Geyik
Köpek
Kurbağa
At
Gemi
Kamyon
Veri seti, 50.000 eğitim ve 10.000 test görüntüsüne bölünmüştür.

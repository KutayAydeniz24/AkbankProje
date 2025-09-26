# AkbankProje

## **Projenin Amacı**  

Bu projenin amacı, verilen görsel veri seti üzerinde derin öğrenme tabanlı bir CNN modeli kullanarak sınıflandırma yapmaktır. Amaç, farklı sınıfları olabildiğince yüksek doğrulukla ayırt eden bir model geliştirmektir. Ayrıca modelin performansını artırmak için veri önişleme, veri çoğaltma (data augmentation) ve hiperparametre optimizasyonu teknikleri uygulanmıştır.

## **Veri Seti Hakkında Bilgi** 

Kullanılan veri seti, farklı sınıfları içeren etiketlenmiş görsellerden oluşmaktadır. Veri seti eğitim, doğrulama ve test alt kümelerine ayrılmıştır. Görseller, modelin daha etkin öğrenmesi için normalize edilmiş ve boyutlandırılmıştır. Data augmentation kapsamında rotation, flip ve zoom gibi dönüşümler kullanılarak veri çeşitliliği artırılmıştır.

## **Kullanılan Yöntemler** 

CNN Mimarisi: Convolutional, Pooling, Dense ve Dropout katmanları

Aktivasyon Fonksiyonları: ReLU (ara katmanlar), Softmax (çıktı katmanı)

Hiperparametre Optimizasyonu: Farklı katman sayıları, filtre boyutları, dropout oranları ve optimizer seçimleri üzerinde denemeler yapılmıştır.

Model Değerlendirme: Accuracy/Loss grafiklerinin incelenmesi, Confusion Matrix, Classification Report ve Grad-CAM görselleştirmeleri ile modelin hangi bölgelerden etkilendiği gösterilmiştir.

## **Elde Edilen Sonuçlar**  

En çok karışan sınıflar: [ör. sınıf A ↔ sınıf B]
Sonuçlar, modelin çoğu sınıfı başarılı bir şekilde ayırt edebildiğini göstermektedir. Grad-CAM analizleri sayesinde modelin karar verirken hangi bölgeleri dikkate aldığı gözlemlenmiştir.

https://www.kaggle.com/code/zekeriyakutayaydeniz/akbankproject

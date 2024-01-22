# SistersLab - Ada Lovelace Academy: Veri Bilimi Akademisi Final Projesi

## Proje Adı:

- Bireyin Obezite Seviyesini Tahmin Etme

## Proje Açıklaması:

- Normal kilolu ve obez yetişkinler karşılaştırıldığında, obezitesi olan yetişkinlerin %51'inde hipertansiyon, %21'inde miyokard enfarktüsü, %8'inde iskemik kalp hastalığı, %3,5'inde konjestif kalp yetmezliği ve %3'ünde felç tespit edilmiştir. Bu istatistikler, günümüzde artan obezitenin önüne geçilmesi amacıyla eğitilen modellerin ve elde edilen sonuçların önemini vurgulamaktadır. Bu veriler ışığında, bireyler kendi sağlık durumları hakkında bilgi sahibi olabilir ve olası hastalıkların önlenmesi için gerekli adımları atabilirler.

## Veri Seti Hakkında:

- Veri seti; Meksika, Peru ve Kolombiya ülkelerinden 14-61 yaşları arasındaki farklı beslenme alışkanlıkları ve fiziksel durumdaki kişilerde obezite düzeylerini içermektedir.
- 17 kolon ve 2111 satırdan oluşmaktadır.
- Veri seti, analiz ve makine öğrenimi için uygun görülmektedir. Kategorik ve sayısal kolonların birlikte bulunması "sınıflandırma problemi" üzerinde çalışmak için daha avantajlıdır.

- BMI_Obesity_Level ve BMI kolonlarının veri setini arttırarak daha iyi sonuçlar elde edilmesine katkı sağlayacağı düşünülerek eklenmiştir.

## Yol Haritası:

1. Gerekli Kütüphaneleri İçe Aktarma
2. Veriyi Alma - Input Data
3. Veriyi Keşfetme ve Inceleme
4. Veri Ön İşleme - Data Prepprocessing
   - Veriyi temizleme ve düzenleme
   - Eksik veya anlamsız verileri dönüştürme, silme veya doldurma
   - Veri formatlarını düzenleme-encoder
5. Veri Görselleştirme - Data Visualization
   - Veri setini anlamak amacıyla grafiklerin çizdirilmesi ve yorumlanması
6. x_data ve y_data olarak verinin eğitim ve test aşamasında ayrılması ardından normalizasyon işleminin yapılması.
7. Veri Bölme - Data Splitting
   - 80-20 şeklinde eğitim ve test verisini bölme.
8. Sınıflandırma - Classification
   - SVM
   - RF
   - KNN
9. Tahmin - Prediction
   - 'Normal_Weight'
   - 'Overweight_Level_I'
   - 'Overweight_Level_II'
   - 'Obesity_Type_I'
   - 'Insufficient_Weight'
   - 'Obesity_Type_II'
   - 'Obesity_Type_III'
10. Değerlendirme Metrikleri - Evaulation Metrics
    - Accuracy
    - Classification Report: Precision - Recall - F1 Score
    - Confusion Matrix

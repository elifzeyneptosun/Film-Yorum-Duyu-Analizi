# Film-Yorum-Duyu-Analizi
 Google Colab'da Türkçe yorumlar temizlenip tokenize edildi, TF-IDF ile vektörleştirildi. Naive Bayes ve Lojistik Regresyon modelleriyle duygu analizi yapıldı; başarı metrikleri olarak precision, recall, f1-score ve ROC-AUC kullanıldı.
 
# Türkçe Yorumlar ile Duygu Analizi

Bu proje, Google Colab ortamında çeşitli kaynaklardan toplanan Türkçe yorumlar üzerinde duygu analizi yapmak amacıyla geliştirilmiştir. 

## Proje Özeti

- Türkçe yorumlar regex ve özel durdurma kelimeleri (stop-words) kullanılarak temizlendi.  
- Metinler tokenize edilerek analiz için hazır hale getirildi.  
- TF-IDF yöntemi ile metinler sayısal vektörlere dönüştürüldü.  
- Naive Bayes ve Logistic Regression modelleri kullanılarak duygu sınıflandırması gerçekleştirildi.  
- Modellerin performansı precision, recall, f1-score ve ROC-AUC metrikleriyle değerlendirildi.

## Kullanılan Teknolojiler

- Python  
- Google Colab  
- scikit-learn  
- nltk  

## Kullanım

1. Google Colab üzerinde notebook açılır.  
2. Gerekli kütüphaneler yüklenir ve import edilir.  
3. Veriler işlenir, modeller eğitilir ve performans metrikleri hesaplanır.

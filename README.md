# Amazon-BestSelling-Books-
## Proje Hakkında
Bu projede, Amazon'da en çok satan kitaplara ait veriler kullanılarak kitapların kategorisinin makine öğrenmesi ile tahmin edilmesi amaçlanmıştır. Projede kitapların fiyatı, yorum sayısı, bestseller listesinde kaldığı hafta sayısı, alt türü ve yazarın kitap sayısı gibi özelliklerden yararlanılmıştır.
Proje kapsamında veri seti incelenmiş, veri analizi ve görselleştirme işlemleri gerçekleştirilmiş, ardından Logistic Regression ve Random Forest modelleri kullanılarak kitap kategorileri tahmin edilmiştir.

## Bulgular
Yapılan modelleme sonucunda Logistic Regression modeli %99, Random Forest modeli ise %98 doğruluk elde etmiştir. Modellerin performansları Cross-Validation sonuçları ile de değerlendirilmiştir.
Cross-Validation sonucunda Logistic Regression için ortalama doğruluk %98.2, Random Forest için ise %97.0 olarak bulunmuştur. Bu sonuçlara göre Logistic Regression modeli daha yüksek performans gösterdiği için final model olarak seçilmiştir.
Feature Importance analizi sonucunda Price, Reviews, Author_Book_Count ve Weeks on List değişkenlerinin model açısından önemli olduğu görülmüştür. Bu bulgular, kitapların fiyatı, aldığı yorumlar, bestseller listesinde kaldığı süre ve yazarın kitap sayısı gibi özelliklerin kategori tahmininde etkili olabileceğini göstermektedir.

## Kullanılan Teknolojiler
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Scikit-learn
-SHAP

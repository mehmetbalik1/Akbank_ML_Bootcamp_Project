# Akbank_ML_Bootcamp_Project
Used Ford Car Price Prediction

 Proje Özeti
Bu projede, Kaggle üzerinden alınan (https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction/data) veri seti kullanılarak ikinci el araç fiyatlarının tahmin edilmesi amaçlanmıştır.  
Veri setinde, Ford marka araçların fiyat, model,	üretim yılı, vites tipi, toplam aldığı yol,	vergi miktarı, yakıt tüketimi,	motor hacmi, yakıt türü yer almaktadır.



Kullanılan Algoritma

Bu problem bir regresyon problemi olduğu için, hedef değişken olanfiyat) sayısal bir değerdir.  
Model olarak; başlangıçta "Linear Regression" uygulanmış, ancak sonuçlar yeterince başarılı olmadığı için daha güçlü bir model olan "Random Forest Regression" tercih edilmiştir.

Random Forest, birçok karar ağacından oluşan topluluk  modeli olup, verideki doğrusal olmayan ilişkileri başarılı şekilde yakalayabilmiştir.



 Modelin Çözdüğü Problem

Model, veri setindeki teknik özelliklerden yola çıkarak bir aracın tahmini satış fiyatını öğrenir ve tahmin eder.  

Gerçek hayatta; ikinci el araç alım-satım platformları, araç kredisi ve sigorta hesaplama gibi alanlarda bu model yardımcı olabilir



 Model Performans Karşılaştırması 
 
           Linear Regression
 
 ![image](https://github.com/user-attachments/assets/7035045f-cada-40fd-a00c-4e6ab36c1c04)

             Random Forest
 
![image](https://github.com/user-attachments/assets/e83c00e7-fe98-481e-98d2-360359d74d83)
 

Ayrıca modelin tahminlerinin gerçek fiyatlarla uyumlu olduğu, scatter plot grafiği ile de görsel olarak gösterilmiştir.


 Proje Nasıl Geliştirilebilir?

 Farklı değişkenler eklenebilir. Örneğin: motor gücü, renk, silindir sayısı,araç gövde tipi(sedan, hatchback,coupe..)

 Sonuç

Bu proje, gözetimli öğrenme yöntemi olan Radom Forest Regression modeli ile başarılı bir araç fiyat tahmin sistemi oluşturmuştur.  
Hem teknik olarak sağlam, hem de gerçek hayatta uygulanabilir bir makine öğrenmesi uygulamasıdır.

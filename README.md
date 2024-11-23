# Aygaz_Bootcamp_23112024
Yusuf Ziya Demirel | Veri Analizi Proje Teslim


Electric Vehicle Data Analysis and Prediction

Bu proje, elektrikli araçlara ilişkin bir veri setini kullanarak veri analizi, özellik mühendisliği ve tahmin modelleri oluşturmayı amaçlamaktadır. Elektrikli araçlar, otomotiv sektöründe giderek büyüyen bir alan olup, araçların fiyat, menzil ve tür gibi özelliklerinin incelenmesi, müşteri ihtiyaçlarının daha iyi anlaşılması ve pazarlama stratejilerinin geliştirilmesi için önem taşımaktadır. Proje süresince veri temizleme, analiz, görselleştirme ve makine öğrenmesi için veri setinin hazırlanması üzerine çalışmalar gerçekleştirilmiştir.

Kullanılan veri seti, Kaggle platformundan alınmış Electric Vehicle Population Data adlı bir veri setidir. Veri seti, elektrikli araçların model yılı, fiyatı (MSRP), menzili, türü ve coğrafi bilgileri gibi çeşitli özellikleri içermektedir. 121.000'den fazla kayıt ve 17 sütun içeren bu veri seti, elektrikli araçlar pazarındaki müşteri davranışlarını analiz etmek ve tahmin modelleri oluşturmak için ideal bir yapıya sahiptir.

Proje Hedefleri
Elektrikli araçlara ilişkin özellikleri analiz ederek müşteri segmentasyonu ve pazarlama stratejilerinin geliştirilmesine yönelik içgörüler sunmak.
Araç fiyatları ve menzili gibi temel değişkenleri kullanarak tahmin modelleri oluşturmak.
Veri setinde yeni özellikler türeterek makine öğrenmesi modellerine uygun bir yapı oluşturmak.

Kullanılan Araçlar ve Kütüphaneler
Proje kapsamında aşağıdaki kütüphaneler ve araçlar kullanılmıştır:

Veri İşleme: pandas, numpy
Görselleştirme: matplotlib, seaborn, missingno
Makine Öğrenmesi: scikit-learn (Linear Regression, Random Forest, K-Means Clustering)
Veri Temizleme: Eksik veri doldurma, aykırı değer analizi
Standartlaştırma ve Normalizasyon: StandardScaler, MinMaxScaler

Bu projede, elektrikli araçlara ilişkin bir veri seti analiz edilerek veri temizleme, görselleştirme ve özellik mühendisliği gibi işlemler gerçekleştirilmiştir. İlk olarak veri setindeki eksik veriler ve aykırı değerler tespit edilerek uygun yöntemlerle ele alınmıştır. Kategorik ve sayısal değişkenler ayrıştırılmış, her bir değişkenin dağılımı ve aralarındaki ilişkiler detaylı bir şekilde incelenmiştir. Veri setini zenginleştirmek amacıyla araç yaşı, fiyat kategorileri, menzil grupları ve fiyat/menzil oranı gibi yeni değişkenler türetilmiştir. Elde edilen sonuçlar, elektrikli araç pazarındaki müşteri segmentlerini anlamak, ürün geliştirme süreçlerine rehberlik etmek ve pazarlama stratejileri oluşturmak için kullanılabilecek değerli içgörüler sağlamıştır. Proje, veri setindeki bilgileri etkili bir şekilde kullanarak işletmelerin stratejik kararlarına katkı sunmayı hedeflemiştir.

Sonuç ve Öneriler

Elektrikli araçların giderek yaygınlaştığı günümüzde, bu veri seti otomotiv sektöründe faaliyet gösteren şirketlere önemli fırsatlar sunmaktadır. Veri setinin analizi sonucunda, araçların fiyat, menzil ve tür gibi özelliklerinin müşteri tercihlerini nasıl etkilediği anlaşılmıştır. Bu proje, müşterilerin ihtiyaçlarını daha iyi anlamak, pazarlama stratejilerini özelleştirmek ve ürün geliştirme süreçlerini optimize etmek için rehberlik edebilir.

Elde edilen analizler ışığında, araçların yaş, menzil ve fiyat segmentlerine göre gruplandırılması, farklı müşteri kitlelerine yönelik stratejilerin geliştirilmesine olanak tanır. Örneğin, kısa menzilli ve ekonomik araçlar düşük bütçeli müşterilere hitap ederken, ultra menzilli ve lüks araçlar premium segmentteki müşterilere yönelik pazarlama stratejilerinde kullanılabilir. Bu tür bir segmentasyon, şirketlerin farklı müşteri gruplarına özelleştirilmiş kampanyalar düzenlemesini ve müşteri memnuniyetini artırmasını sağlayabilir.

Ayrıca, fiyat ve menzil oranı gibi yeni türetilen metrikler, şirketlerin ürün geliştirme sürecinde daha bilinçli kararlar almasını destekleyebilir. Örneğin, belirli bir fiyat aralığında daha uzun menzil sunan araç modelleri tasarlamak, müşteri memnuniyetini artırabilir ve satışları destekleyebilir. Araç türleri (Plug-in Hybrid vs. Battery Electric) arasında yapılan analizler, hangi türün pazarda daha fazla talep gördüğünü anlamaya yardımcı olabilir.

Bu veri setine dayanarak oluşturulacak tahmin modelleri, şirketin iş süreçlerinde değer yaratabilir. Örneğin, Random Forest Regressor gibi algoritmalar kullanılarak araçların elektrik menzili tahmin edilebilir ve bu bilgi, yeni modeller geliştirilirken kullanılabilir. Logistic Regression veya XGBoost gibi algoritmalarla araç türü tahmin edilerek üretim ve stok yönetimi süreçleri optimize edilebilir. Ayrıca, K-Means Clustering gibi algoritmalar kullanılarak müşteri segmentasyonu yapılabilir ve pazarlama stratejileri daha etkili hale getirilebilir.

Sonuç olarak, bu proje, elektrikli araç pazarındaki fırsatları değerlendirmek ve şirketin stratejik kararlarını desteklemek için güçlü bir temel sunmaktadır. Önerilen algoritmalar ve türetilen özellikler, pazarlama, ürün geliştirme ve satış süreçlerini iyileştirerek şirketin karlılığını artırabilir. Proje, daha büyük veri setleri ve gelişmiş analizlerle genişletilerek daha fazla iş değeri yaratma potansiyeline sahiptir. Bu süreçte, şirketin veri bilimi ve makine öğrenmesi ekipleriyle iş birliği yaparak daha detaylı modeller geliştirilebilir ve bu modeller iş süreçlerine entegre edilebilir.

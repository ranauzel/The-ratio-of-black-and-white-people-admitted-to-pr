
### Aykırı Değer Tespiti ve p-değeri Hesaplama
Veri Seti Kaggle'den alınan "https://www.kaggle.com/datasets/konradb/prison-population-in-the-us?select=admissions_releases_states.csv" veri setinden faydalanılmıştır. Bu veri setinde Hapse giren beyaz, siyahi  bireyler ile hapisten çıkanlar arasında bir ilişki oldup olmadığı incelenmiştir. Veri setinde detaylı olarak hapisene koşulları, suç oranlarının nedenleri gibi alt bilgilere sahip olunmadığı için kesin olarak bir çıkarım yapılmamaktadır.Ancak veri ön işleme yöntemlerini kullanarak bir veri analizi gerçekleştirilmiştir.

Bu proje, veri setindeki aykırı değerleri tespit etmek için kullanılan iki temel yöntemi—Z-Skoru ve IQR (Interquartile Range)—kullanarak aykırı değer analizi yapmayı ve bu aykırı değerlerin istatistiksel anlamlılığını p-değeri hesaplama yöntemiyle değerlendirmeyi amaçlamaktadır.

Proje Özeti
Veri bilimi alanında aykırı değerler (outliers) analiz edilen veri setinin doğruluğunu ve güvenilirliğini etkileyebilecek değerlerdir. Bu projede verideki aykırı değerleri tespit etmek için Z-Skoru ve IQR yöntemleri kullanılmıştır. Ayrıca tespit edilen aykırı değerlerin anlamlı olup olmadığını belirlemek için p-değeri hesaplaması yapılmıştır.

Kullanılan Yöntemler
1. Z-Skoru Yöntemi
Z-Skoru, bir veri noktasının ortalamadan ne kadar uzak olduğunu ölçen bir istatistiksel yöntemdir. Z-Skoru, verilerin normal dağılıma sahip olduğu varsayımıyla çalışır. Bu yöntemde Z-Skoru 3’ten büyük (ya da küçük) olan değerler aykırı değer olarak kabul edilir.

2. IQR (Interquartile Range) Yöntemi
IQR, veri setindeki 1. çeyrek (Q1) ve 3. çeyrek (Q3) arasındaki farkı ölçen bir yöntemdir. Aykırı değerler, Q1 - 1.5 * IQR ve Q3 + 1.5 * IQR sınırlarının dışındaki değerler olarak kabul edilir.

4. p-değeri Hesaplama
Aykırı değerlerin istatistiksel anlamlı olup olmadığını tespit etmek için p-değeri hesaplanmıştır. P-değeri, gözlemlenen verilerin null hipotez altında tesadüfi olup olmadığını anlamaya yardımcı olur. Genellikle 0.05’ten küçük bir p-değeri gözlemlenen farkın veya ilişkinin istatistiksel olarak anlamlı olduğunu gösterir.

Proje Adımları
Veri Seti: Projede kullanılan veri setinde çeşitli sayısal özellikler bulunmaktadır. Bu verilerdeki aykırı değerler tespit edilmiştir.

Aykırı Değerlerin Tespiti: Hem Z-Skoru hem de IQR yöntemleriyle verideki aykırı değerler tespit edilmiştir.

p-değeri Hesaplama: Tespit edilen aykırı değerlerin anlamlı olup olmadığını belirlemek için p-değeri hesaplanmıştır.

Sonuçların Değerlendirilmesi: Hesaplanan p-değeri ile aykırı değerlerin anlamlılıkları değerlendirilmiştir.


# Profesyonel-Metin-Analiz-Arac-
Python tabanlı, NLP (Doğal Dil İşleme) odaklı ve istatistiksel raporlama sunan profesyonel metin analiz aracı. 📊🚀

📊 Profesyonel Metin Analiz Aracı (Text Analyzer Pro)
Bu proje, ham bir metni alıp üzerinde derinlemesine istatistiksel analizler yapan Python tabanlı bir araçtır. Basit bir kelime sayacı olarak başlamış, Veri Temizliği (Data Cleaning) ve Doğal Dil İşleme (NLP) prensipleriyle profesyonel bir seviyeye taşınmıştır.

🚀 Özellikler
•	Noktalama Temizliği: Metni tüm noktalama işaretlerinden arındırarak saf veriye ulaşır.
•	Standardizasyon: Büyük/küçük harf duyarlılığını ortadan kaldırır.
•	Kelime Frekansı: En çok kullanılan kelimeleri collections.Counter ile analiz eder.
•	Görsel Raporlama: Konsol üzerinde basit çubuk grafikler (bar charts) oluşturur.
•	Detaylı İstatistik: Toplam kelime, benzersiz kelime ve en uzun kelimeyi raporlar.

🛠 Kullanılan Teknolojiler & Kütüphaneler
•	Python 3.x
•	string: Metin manipülasyonu ve noktalama temizliği için.
•	collections (Counter): Veri sayımı ve frekans analizi için.

📝 Kodun Çalışma Mantığı
Kodun işleyişi modern bir veri işleme hattını (pipeline) takip eder:
1.	Girdi (Input): Kullanıcıdan metin alınır.
2.	Ön İşleme (Preprocessing): Noktalamalar silinir ve tüm karakterler küçük harfe dönüştürülür.
3.	Tokenizasyon: Metin, kelime birimlerine ayrılır.
4.	Analiz: Kelime frekansları ve istatistikleri hesaplanır.
5.	Sunum: Sonuçlar kullanıcıya görsel bir rapor olarak sunulur.


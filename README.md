GE90 Jet Motoru - Dijital İkiz Projesi 🚀
Bu projede, GE90 benzeri bir turbofan motorunun dijital ikizini oluşturarak, kestirimci bakım ve arıza tahmini üzerine bir analiz gerçekleştirdim.

🔧 Projenin Amacı
Gerçek zamanlı verilerle (örneklenmiş sıcaklık ve titreşim ölçümleriyle), bir motorun sağlık durumunu tahmin edebilen ve kalan kullanım ömrünü (RUL) öngörebilen bir dijital sistem geliştirmek.

🛠️ Kullanılan Araçlar
SolidWorks: Jet motorunun 3D CAD tasarımı

MATLAB / Simulink: Fiziksel sistem simülasyonu (hareket, dönme, kuvvet iletimi)

Google Colab + Python: Verilerin işlenmesi, tahmin modellerinin eğitimi, grafik analizleri

Scikit-learn: Sınıflandırma ve regresyon algoritmaları

Pandas & Matplotlib: Veri işleme ve görselleştirme

📁 Proje İçeriği
motor_model.ipynb → Sıcaklık ve titreşim verileriyle arıza tahmini

rul_predictor.ipynb → Kalan kullanım ömrü (RUL) tahmin modeli

station41_42_48_5.csv → GE90 motoruna ait istasyon verilerinden örneklenmiş sıcaklık değerleri

vibration_signal.csv → Normal ve arızalı motor titreşim örnekleri

graph_*.png → Tahmin karşılaştırmaları ve veri görselleri

📊 Neler Yapıldı?
GE90 motoruna benzer bir model tasarlandı

Gerçekçi sıcaklık profilleri oluşturuldu

Titreşim verisiyle arıza senaryoları test edildi

Sıcaklık + titreşim verileri kullanılarak RUL tahmini yapıldı

Model doğruluğu grafiklerle karşılaştırıldı

🔍 Sonuç
Simüle edilen dijital ikiz sayesinde, motorun hangi anlarda arıza verebileceği tahmin edilebildi. Bu sayede proaktif bakım stratejilerinin nasıl uygulanabileceğine dair güçlü bir örnek geliştirilmiş oldu.


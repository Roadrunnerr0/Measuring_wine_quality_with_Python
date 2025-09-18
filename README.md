# Measuring_wine_quality_with_Python
🍷 “Şarap Kalitesini Keşfetmek: Veri Bilimi ile Aromaları Çözümlemek”

Hayatınızda hiç bir şarabın neden daha iyi veya daha kötü olduğunu merak ettiniz mi? Peki, bu farkı sadece tat ve koku değil, bilim ve verilerle keşfedebileceğinizi biliyor muydunuz? İşte tam da bu noktada bu proje devreye giriyor. Bizim elimizde 13 farklı özelliğe sahip yüzlerce şarap örneği ve her birinin kalitesini gösteren bir veri seti var. Amacımız: Bu sayısal verileri kullanarak şarabın kalitesini etkileyen faktörleri görselleştirmek ve anlayabilmek.

📊 Veri Analizi ve Keşif:
Projeye başlarken, veriyi tanımak için ilk adım olarak temel istatistikleri çıkardık. Hangi özellikler daha sık görülüyor, hangi özellikler uç değerler içeriyor gibi soruların cevaplarını bulduk. Ardından, scatter plotlar ve histogramlar sayesinde değişkenler arasındaki ilişkileri görselleştirdik. Örneğin, density ve citric acid arasında nasıl bir ilişki var? pH değerleri ve alcohol miktarı şarap kalitesini nasıl etkiliyor? Bu soruların cevabı artık grafiklerde gözle görülebiliyor.

🌡️ Korelasyon ve İlişkiler:
Sadece bireysel özelliklere bakmak yetmez. Özelliklerin birbirleriyle olan ilişkilerini anlamak için korelasyon analizleri ve ısı haritaları yaptık. Böylece, bazı değişkenlerin kaliteyi tahmin etmede daha etkili olduğunu keşfettik. Mesela, alcohol ve citric acid gibi bazı değerler, kalite skorlarıyla oldukça güçlü bir ilişkiye sahip.

🎨 Görselleştirme ile Anlamlandırma:
Sadece sayılar değil, görseller de çok şey anlatır. Bu projede, scatter plotlar, box plotlar ve KDE dağılımları ile her bir değişkenin kaliteye göre dağılımını detaylı şekilde gösterdik. Özellikle KDE plotları sayesinde, hangi kalite sınıfındaki şarapların hangi değer aralığında yoğunlaştığını rahatlıkla görebiliyoruz. Her grafikte, veri setinde gerçekten var olan kalite sınıfları gösteriliyor; böylece eksik veriler veya boş grafiklerle kafa karışıklığı yaşanmıyor.

🧩 Her Bir Sütun, Yeni Bir Hikaye Anlatıyor:
fixed acidity, volatile acidity, citric acid, pH, alcohol ve diğer tüm değişkenler, şarabın tadını ve kalitesini etkileyen birer karakter gibi. Her bir sütun için ayrı ayrı çizdiğimiz KDE grafikleri, adeta bir şarap laboratuvarına girip, şişelerin içeriklerini mikroskopla inceliyormuşuz gibi hissettiriyor. Hangi kalite sınıfı hangi aralıkta yoğunlaşmış? Hangi değişken kaliteyi tahmin etmede daha belirleyici? Tüm bunlar artık görsel olarak parmaklarınızın ucunda.

🔮 Neden Bu Proje Çok İlginç?
Çünkü herkes şarap içiyor ama herkes veriye dayalı analiz yapmıyor. Bu proje, görsel ve sayısal analizleri birleştirerek şarap kalitesini bilimsel olarak anlamayı sağlıyor. Ayrıca, veri setinde eksik kalite sınıfları olsa bile, proje bunu otomatik olarak yönetiyor; yani her grafik sadece mevcut verileri gösteriyor ve sizi yanıltmıyor.

💡 Uygulamaya Davet:
Bu proje sadece bir veri analizi değil, bir keşif yolculuğu. Şarap severler, veri bilimi tutkunu öğrenciler, meraklı araştırmacılar… Herkes kendi verilerini alıp bu adımları deneyebilir, kendi görsellerini oluşturabilir ve şarap dünyasını sayısal bir gözle yeniden keşfedebilir.

Sonuç olarak, bu proje sadece şarap kalitesini incelemekle kalmıyor; aynı zamanda veri bilimi ile günlük yaşam deneyimlerini birleştirmeyi gösteriyor. Siz de merak ediyorsanız, veriyi keşfetmeye ve şarapların gizli hikayesini çözmeye hemen başlayabilirsiniz.

----------------------------------------------
Bu uygulamada kullanılan Dataset:https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

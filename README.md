

🌍 Dünya Mutluluk Raporu Analizi: Toplumsal Refahın Faktörleri ve Yıllık Değişimleri
Bu proje, Birleşmiş Milletler Sürdürülebilir Kalkınma Çözümleri Ağı tarafından yayımlanan Dünya Mutluluk Raporları'nın 2015, 2016 ve 2017 yıllarına ait verilerini kullanarak ülkelerin mutluluk düzeylerini ve bu düzeyleri etkileyen temel faktörleri derinlemesine analiz etmeyi amaçlamaktadır. Proje, mutluluk kavramının çok boyutlu yapısını anlamayı ve toplumsal refahın artırılmasına yönelik potansiyel içgörüler sunmayı hedeflemektedir.

🎯 Proje Amacı
Bu analizle aşağıdaki ana sorulara yanıtlar aranmıştır:

Genel Mutlulukta ve Katkıda Bulunan Faktörlerde Lider Ülkeler: Hangi ülkeler veya bölgeler genel mutlulukta ve mutluluğa katkıda bulunan altı temel faktörün her birinde en yüksek sırada yer alıyor? En mutlu toplumların güçlü olduğu alanlar nelerdir?

Yıllık Mutluluk Trendleri: 2015-2016 ile 2016-2017 raporları arasında ülke sıralamaları veya puanları nasıl değişti? Yıllar içindeki mutluluk trendleri ve belirgin değişimler nelerdir?

Önemli Artış ve Azalışlar: Herhangi bir ülke mutlulukta önemli bir artış veya azalma yaşadı mı? Bu değişimlerin ardındaki olası nedenler neler olabilir?

📊 Veri Seti
Bu projede kullanılan veriler, Kaggle'da bulunan World Happiness Report veri setinden alınmıştır. Analiz için özellikle 2015, 2016 ve 2017 yıllarına ait raporlar kullanılmıştır.

Veri setindeki temel sütunlar ve anlamları:

Country: Ülkenin adı.

Sıralama: Ülkenin mutluluk sıralamasındaki yeri.

Mutluluk Skoru: Ülkenin mutluluk puanı (0-10 arası).

GDP per Capita (Ekonomik Üretim): Kişi başına düşen GSYİH'nin mutluluk skoruna katkısı.

Sosyal Destek: Zor zamanlarda güvenilebilecek birilerine sahip olma algısının mutluluk skoruna katkısı.

Yaşam Beklentisi: Sağlıklı yaşam beklentisinin mutluluk skoruna katkısı.

Özgürlük: Yaşam tercihleri yapma özgürlüğü algısının mutluluk skoruna katkısı.

Yolsuzluk Algısı: Hükümette ve iş dünyasında yolsuzluğun yaygınlığı algısının mutluluk skoruna katkısı (düşük algı yüksek puan).

Cömertlik: Başkalarına yardım etme eğiliminin mutluluk skoruna katkısı.

Yıl: Verinin ait olduğu yıl.

🛠️ Kullanılan Kütüphaneler
Bu projenin analiz ve görselleştirme adımlarında aşağıdaki Python kütüphaneleri kullanılmıştır:

pandas: Veri manipülasyonu ve analizi için.

numpy: Sayısal hesaplamalar için.

matplotlib: Temel veri görselleştirmeleri için.

seaborn: Estetik ve istatistiksel veri görselleştirmeleri için.

🚀 Proje Yapısı ve Adımlar
Ortam Kurulumu: Gerekli kütüphanelerin içeri aktarılması ve görselleştirme ayarlarının yapılması.

Veri Yükleme ve Ön İşleme:

2015, 2016 ve 2017 yıllarına ait CSV dosyaları yüklendi.

Her veri setine bir 'Yıl' sütunu eklendi.

Sütun isimleri, yıllar arası tutarlılık sağlamak amacıyla Türkçe'ye çevrildi ve standardize edildi.

Üç yıllık veri seti tek bir DataFrame'de (df_all) birleştirildi.

Eksik değer kontrolü yapıldı (veri setinde eksik değer bulunmamıştır).

Keşifsel Veri Analizi (EDA):

Her yıl için genel mutluluk skorunda en yüksek ilk 10 ülke listelendi.

Mutluluğa katkıda bulunan her bir faktör (GDP per Capita, Sosyal Destek, Yaşam Beklentisi, Özgürlük, Yolsuzluk Algısı, Cömertlik) için en yüksek ilk 5 ülke belirlendi.

Yıllar Arası Değişim Analizi:

2015-2016 ve 2016-2017 dönemleri için mutluluk skorlarındaki ve sıralamalardaki değişimler hesaplandı.

Her iki dönem için de mutluluk skorunda en büyük artış ve azalış yaşayan ülkeler ile sıralamada en çok iyileşme gösteren ülkeler tespit edildi.

Veri Görselleştirme:

Her yıl için en mutlu 10 ülkenin mutluluk skorlarını gösteren çubuk grafikler oluşturuldu.

2017 yılı verisi kullanılarak mutluluk skoru ve belirleyici faktörler arasındaki korelasyonu gösteren bir ısı haritası çizildi.

Seçili ülkelerin (örneğin Finlandiya, Burundi, Türkiye, Danimarka, Norveç) yıllara göre mutluluk skoru değişimini gösteren çizgi grafiği oluşturuldu.

💡 Analizden Çıkarılan Temel İçgörüler
İskandinav Ülkelerinin Tutarlı Liderliği: Finlandiya, Danimarka, Norveç, İzlanda ve İsviçre gibi ülkeler, yıllar boyunca mutluluk sıralamalarının zirvesinde yer alarak istikrarlı bir refah seviyesi sergilemişlerdir.

Ekonomik ve Sosyal Faktörlerin Önemi: GDP per Capita, Sosyal Destek ve Yaşam Beklentisi, mutluluk skoru ile en güçlü pozitif korelasyona sahip faktörler olarak öne çıkmaktadır. Bu, maddi refah, güçlü toplumsal bağlar ve sağlık altyapısının genel mutluluk için kritik olduğunu göstermektedir.

Değişken Mutluluk Dinamikleri: Bazı ülkeler mutluluk skorlarında yıldan yıla önemli artışlar veya azalmalar yaşayabilmektedir. Örneğin, Venezuela her iki dönemde de mutluluk skorunda keskin düşüşler yaşarken, Cezayir bir dönem büyük artış gösterip diğer dönem düşüş kaydetmiştir. Bu durum, mutluluğun sadece uzun vadeli faktörlere değil, aynı zamanda kısa vadeli politik, ekonomik veya sosyal olaylara da duyarlı olduğunu göstermektedir.

Yolsuzluk Algısı ve Özgürlüğün Etkisi: Yolsuzluk algısının düşük olması (yani yüksek puan) ve bireysel özgürlükler, mutluluğa pozitif yönde katkıda bulunan diğer önemli faktörlerdir.

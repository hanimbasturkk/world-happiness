
# 🌍 Dünya Mutluluk Raporu Analizi: Toplumsal Refahın Faktörleri ve Yıllık Değişimleri

Bu proje, Birleşmiş Milletler Sürdürülebilir Kalkınma Çözümleri Ağı tarafından yayımlanan Dünya Mutluluk Raporları'nın 2015, 2016 ve 2017 yıllarına ait verilerini kullanarak ülkelerin mutluluk düzeylerini ve bu düzeyleri etkileyen temel faktörleri derinlemesine analiz etmeyi amaçlamaktadır. Proje, mutluluk kavramının çok boyutlu yapısını anlamayı ve toplumsal refahın artırılmasına yönelik potansiyel içgörüler sunmayı hedeflemektedir.

---

## 🎯 Proje Amacı

Bu analizle aşağıdaki ana sorulara yanıtlar aranmıştır:

- **Genel Mutlulukta ve Katkıda Bulunan Faktörlerde Lider Ülkeler:** Hangi ülkeler genel mutlulukta ve katkı yapan faktörlerde öne çıkıyor?
- **Yıllık Mutluluk Trendleri:** Ülkeler yıllar içinde nasıl değişti?
- **Önemli Artış ve Azalışlar:** Hangi ülkelerde dramatik değişimler gözlemlendi? Olası nedenler neler olabilir?

---

## 📊 Veri Seti

Veriler, Kaggle’daki World Happiness Report veri setinden alınmıştır. 2015, 2016 ve 2017 yılları kullanılmıştır.

**Temel sütunlar:**

- `Country`: Ülke adı  
- `Sıralama`: Mutluluk sırası  
- `Mutluluk Skoru`: 0-10 arası puan  
- `GDP per Capita`: Ekonomik üretim  
- `Sosyal Destek`: Toplumsal destek  
- `Yaşam Beklentisi`: Sağlıklı yaşam süresi  
- `Özgürlük`: Tercih özgürlüğü  
- `Yolsuzluk Algısı`: Yolsuzluk algısı (düşük algı = yüksek mutluluk)  
- `Cömertlik`: Yardım etme eğilimi  
- `Yıl`: Verinin yılı  

---

## 🛠️ Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 🚀 Proje Adımları

1. **Ortam Kurulumu**  
   Kütüphaneler içeri aktarıldı, ayarlar yapıldı.

2. **Veri Yükleme ve Ön İşleme**  
   - CSV dosyaları yüklendi  
   - 'Yıl' sütunu eklendi  
   - Sütun adları Türkçeleştirildi  
   - Tüm yıllar birleştirildi (`df_all`)  
   - Eksik veri kontrolü yapıldı (yok)

3. **Keşifsel Veri Analizi (EDA)**  
   - En mutlu 10 ülke listelendi  
   - Her faktörde en yüksek 5 ülke belirlendi  

4. **Yıllar Arası Değişim Analizi**  
   - 2015-2016 ve 2016-2017 karşılaştırmaları yapıldı  
   - En fazla artış/azalış yaşayan ülkeler tespit edildi  

5. **Veri Görselleştirme**  
   - En mutlu 10 ülke için bar grafik  
   - 2017 yılı için korelasyon ısı haritası  
   - Seçili ülkeler için çizgi grafik  

---

## 💡 Temel İçgörüler

- **İskandinav Ülkeleri Zirvede:** Finlandiya, Danimarka, Norveç, İzlanda ve İsviçre mutlulukta istikrarı sürdürüyor.
- **Ekonomik ve Sosyal Faktörler Önemli:** GDP, sosyal destek ve yaşam beklentisi en yüksek korelasyona sahip.
- **Mutluluk Dinamikleri Değişken:** Venezuela gibi ülkelerde yıllar içinde ciddi düşüşler görülüyor.
- **Özgürlük ve Yolsuzluk Etkisi:** Algılanan özgürlük ve düşük yolsuzluk yüksek mutlulukla ilişkilidir.




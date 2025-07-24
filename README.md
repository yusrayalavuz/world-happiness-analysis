# Dünya Mutluluk Raporu Veri Analizi (2015-2019)

Bu proje, 2015-2019 yılları arasındaki Dünya Mutluluk Raporu verilerini kullanarak ülkelerin mutluluk seviyelerini, bu seviyeleri etkileyen faktörleri ve zaman içindeki değişimleri keşfetmeyi amaçlayan kapsamlı bir Veri Analizi (EDA) çalışmasıdır.

## 📊 Proje Genel Bakışı

Dünya Mutluluk Raporu, Birleşmiş Milletler Sürdürülebilir Kalkınma Çözümleri Ağı tarafından yayınlanan ve ülkelerin mutluluk düzeylerini çeşitli faktörlere göre sıralayan yıllık bir rapordur. Bu çalışma, söz konusu raporların 2015 ile 2019 yılları arasındaki verilerini bir araya getirerek aşağıdaki temel sorulara yanıt aramaktadır:

* Hangi ülkeler en mutlu ve en mutsuz?
* Mutluluğa en çok katkıda bulunan faktörler nelerdir (Ekonomi, Sosyal Destek, Yaşam Beklentisi vb.)?
* Ülkelerin mutluluk sıralamaları ve puanları zaman içinde nasıl değişti?
* Herhangi bir ülke mutlulukta önemli bir artış veya azalma yaşadı mı?
* Bölgeler bazında mutluluk ve faktörler nasıl farklılık gösteriyor?

## 🚀 Kullanılan Teknolojiler ve Kütüphaneler

* **Python:** Veri analizi ve manipülasyonu için temel programlama dili.
* **Pandas:** Veri çerçeveleri üzerinde güçlü ve esnek veri manipülasyonu için.
* **NumPy:** Sayısal işlemler ve dizi manipülasyonları için.
* **Matplotlib:** Statik, interaktif ve animasyonlu görselleştirmeler oluşturmak için.
* **Seaborn:** Matplotlib üzerine kurulu, daha çekici ve bilgilendirici istatistiksel grafikler oluşturmak için.

## 📁 Veri Seti

Bu projede kullanılan veri setleri, Kaggle'da bulunan "World Happiness Report" (Dünya Mutluluk Raporu) veri setleridir. 2015'ten 2019'a kadar her yıl için ayrı CSV dosyaları bulunmaktadır.

* `2015.csv`
* `2016.csv`
* `2017.csv`
* `2018.csv`
* `2019.csv`

**Veri Kapsamı:** Her veri seti, ülkelerin mutluluk sıralaması, mutluluk skoru ve bu skoru etkileyen altı temel faktöre (Ekonomi (GDP per Capita), Sosyal Destek (Family), Sağlık (Life Expectancy), Özgürlük (Freedom), Yolsuzluk Algısı (Perceptions of Corruption), Cömertlik (Generosity)) ilişkin bilgileri içermektedir. Yıllar arasında sütun adlandırmalarında ve veri yapısında küçük farklılıklar bulunmaktadır, bu farklılıklar veri ön işleme aşamasında ele alınmıştır.


## 🎯 Projenin Amaçları

* **Veri Birleştirme ve Temizleme:** Farklı yıllara ait veri setlerini standartlaştırarak tek bir ana veri çerçevesinde birleştirmek.
* **Keşifsel Veri Analizi (EDA):** Veri setinin yapısını anlamak, temel istatistikleri çıkarmak ve görselleştirmelerle önemli eğilimleri ve ilişkileri belirlemek.
* **Zaman Serisi Analizi:** Ülkelerin ve bölgelerin mutluluk puanlarındaki değişimleri zaman içinde incelemek.
* **Faktör Analizi:** Hangi faktörlerin mutluluğa daha fazla katkıda bulunduğunu belirlemek.
* **Çıkarımlar ve Öneriler:** Elde edilen bulgulardan yola çıkarak genel sonuçlar çıkarmak ve politika önerileri sunmak.


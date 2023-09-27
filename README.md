# Sağlık Verileri İle BMI Tahmini ve Ürün Fiyat Analizi

Bu proje, verilen sağlık verileri (yaş, kilo, boy) ile bir kişinin BMI (Vücut Kitle İndeksi) değerini tahmin etmek ve farklı fiyat aralıklarına göre ürünleri sınıflandırmak için kullanılan bir yapay sinir ağı modelini içermektedir.

## İçerikler
1. **BMI Tahmini:** Sağlık verileri (yaş, kilo, boy) kullanarak bir kişinin BMI değerini tahmin eden bir yapay sinir ağı modeli.
2. **Ürün Fiyat Analizi:** Verilen ürünlerin fiyatlarına göre gruplandırılarak grafikle gösterilmesi.

## Nasıl Çalışır?

1. **BMI Tahmini:** `health-data.csv` adlı dosyadan veri çekilir ve model bu verilere göre eğitilir. Sonrasında test verisi ile modelin performansı ölçülür.
2. **Ürün Fiyat Analizi:** `urunler.csv` adlı dosyadan veri çekilir ve fiyat aralıklarına göre ürünler gruplandırılır. Fiyat aralıklarına göre ürün sayısı bir grafikle gösterilir.

## Kullanılan Teknolojiler ve Kütüphaneler
- Python
- TensorFlow
- Keras
- matplotlib
- csv
- numpy

## Lisans
Bu proje MIT lisansı altında lisanslanmıştır. (Eğer projeniz bir lisansa sahipse bu bölümü ekleyebilirsiniz.)


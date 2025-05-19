# Uçak Bilet Rezervasyon Sistemi - Java OOP Final Projesi

Bu proje, Java dili ile nesne yönelimli programlama (OOP) prensipleri kullanılarak geliştirilmiş bir uçak bileti rezervasyon sistemidir. Konsol üzerinden çalışan uygulama, uçuşları listeleme, rezervasyon yapma ve verileri dosyaya kaydetme gibi işlevleri yerine getirir.

## Özellikler

- Uçak Tanımı: Model, marka, seri numarası ve koltuk kapasitesi bilgileri içerir.
- Lokasyon Tanımı: Ülke, şehir ve havaalanı bilgileri tanımlanır.
- Uçuşlar: Kalkış ve varış lokasyonları, saat ve uçak bilgileriyle tanımlanır.
- Rezervasyon: Ad, soyad, yaş bilgileriyle rezervasyon yapılır.
- Koltuk Kontrolü: Uçağın koltuk kapasitesine göre rezervasyon yapılabilir.
- Dosya Kaydı: Rezervasyonlar, uçaklar ve lokasyonlar JSON ve CSV formatında dosyalara kaydedilir.

## Kullanılan Yapılar

- abstract class: TemelNesne (ortak alanlar: id, aktiflik)
- class'lar: Ucak, Lokasyon, Ucus, Rezervasyon (hepsi TemelNesne’den türetilmiştir)
- Dosya işlemleri: JSON ve CSV dosya kaydı

## Çalışma Mantığı

1. Program başlarken örnek uçaklar, lokasyonlar ve uçuşlar otomatik yüklenir.
2. Konsol üzerinden uçuşlar görüntülenebilir.
3. Uygun bir uçuş seçilip rezervasyon yapılabilir.
4. Rezervasyon yapıldıktan sonra uçuşun koltuk kapasitesi azaltılır.
5. Program kapatıldığında tüm veriler hem `.json` hem de `.csv` dosyalarına kaydedilir.

## Kaydedilen Dosyalar

- `rezervasyonlar.json` / `rezervasyonlar.csv`
- `ucaklar.json` / `ucaklar.csv`
- `lokasyonlar.json` / `lokasyonlar.csv`


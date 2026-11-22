# Hedef500 – LGS Öğrenci Koçluk Programı

8. sınıf öğrencilerinin LGS hazırlığını bir eğitim koçunun gözünden takip etmek için Windows masaüstü programı.
(3.22 ve önceki sürümlerdeki adı: LGS Öğrenci Koçluk Programı. Eski sürümü kullananlar güncellemeyle Hedef500'e geçer; verileri ve lisansları korunur.)

- Yayınevlerinin deneme sonuç PDF'lerini (karne ve kurum listeleri) tek seferde okur
- Konu bazlı eksikleri bulur, konu durumlarını kendiliğinden günceller
- Öncelik sıralı haftalık çalışma programı hazırlar (dikey liste ya da yatay haftalık çizelge)
- Öğrenci gelişim raporu, sınıf raporu ve çalışma programını A4 ve telefon biçiminde PDF olarak üretir
- Sınıf net listesi (son net, önceki deneme, ▲▼ değişim, puan) çıkarır; sınıfları karşılaştırır, konu etüt grupları ve deneme katılım raporu hazırlar
- Öğrencileri şablon Excel dosyasıyla toplu ekler, veli ve hedef bilgilerini toplu günceller
- Raporları veliye WhatsApp üzerinden yarı otomatik gönderir
- Okuyamadığı bir yayının belgesini ve program hatalarını, kişisel bilgiler gizlenmiş bir raporla geliştiriciye bildirmenizi sağlar
- Verileri yalnızca bu bilgisayarda tutar, her kapanışta sıkıştırılmış yedek alır

## İndirme

**[En son sürümü indirin](../../releases/latest)** — sayfadaki dosyalar:

| Dosya | Ne? |
|---|---|
| `LGS-Kocluk.exe` | Program. İndirdiğiniz yerden çift tıklayın: ilk açılışta bilgisayarınıza yerleştirilmesini önerir. Program kendi klasörüne kopyalanır, Masaüstüne ve Başlat menüsüne **Hedef500 - LGS Koçluk** kısayolu eklenir, indirilen dosya Geri Dönüşüm Kutusu'na taşınır. Yönetici izni gerekmez; öğrenci verileri bulut klasörlerine (OneDrive) yüklenmez. |
| `LGS-Kocluk-Kullanim-Kilavuzu.pdf` | Kullanım kılavuzu: programın her bölümü adım adım. Aynı kılavuz programın içinde de var: **Yardım ▾ → Kullanım Kılavuzu** (ya da F1). |
| `LGS-Kocluk-Ogrenci-Listesi-Sablonu.xlsx` | Öğrenci listesi şablonu: öğrencilerinizi yazıp programda **Toplu İşlemler → Excel'den Bilgi Aktar…** ile yükleyin. Aynı şablon program içinden de oluşturulabilir. |
| `surum.json`, `iptal.json` | Programın güncelleme ve lisans denetimi için kullandığı dosyalar; indirmeniz gerekmez. |

> Windows ilk açılışta "Windows bilgisayarınızı korudu" uyarısı gösterebilir: **Ek bilgi → Yine de çalıştır** deyin.

## Demo ve lisans

- **Demo:** İlk kullanımdan itibaren **15 gün** boyunca, en fazla **30 öğrenci** ile tüm özellikler kullanılabilir.
- **Kurum tanıtım lisansı:** Okullar programı bütün sınıflarıyla, öğrenci sınırı olmadan **30 gün** inceleyebilir.
  Programda lisans penceresinden talep türü olarak **Kurum tanıtım lisansı**nı seçip talep gönderin.
- **Yıllık lisans:** 10 öğrenci (Bireysel Koç), 50, 150, 300 öğrenci ya da sınırsız paketler.
  Lisans tek bir bilgisayara bağlıdır; bilgisayar değiştirdiğinizde lisansınız yeni bilgisayara taşınır.
- **Nasıl alınır?** Programda üst çubuktaki lisans etiketine tıklayın, bilgilerinizi kontrol edip
  **Talebi Gönder**'e basın. Lisans dosyanız e-posta adresinize gelir; aynı pencerede
  **Lisans Dosyasını Seç…** ile açmanız yeterlidir. Talep ile birlikte öğrencilere ait hiçbir bilgi gönderilmez.
- Demo, tanıtım ya da lisans süresi biterse program **salt okuma** moduna geçer; hiçbir veri silinmez.

## Güncelleme

Program yeni sürümleri kendisi denetler ve tek tıkla güncellenir; verileriniz korunur.
Güncelleme denetiminde yalnızca sürüm bilgisi indirilir, **hiçbir öğrenci verisi gönderilmez**.
Her sürüm yayıncının dijital imzasıyla doğrulanır; imzası tutmayan dosya kurulmaz.

Program internet olmadan da çalışır. Kurum ağı GitHub'ı engelliyorsa program sürüm bilgisini yedek bir
adresten alır; yeni sürümün kendisi indirilemezse programı evde ya da telefon internetine bağlıyken açıp güncelleyin.

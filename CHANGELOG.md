# Changelog

Bu dosya, **SteelSeries GG Türkçe Yama** projesindeki önemli değişiklikleri takip etmek için kullanılır.

Sürüm numaralandırması mümkün olduğunca [Semantic Versioning](https://semver.org/) yaklaşımına göre tutulur.

Değişiklikler yayınlanmadan önce `[Unreleased]` bölümünde toplanır ve yeni sürüm yayınlandığında ilgili sürüm başlığı altına taşınır.

---

## [Unreleased]

Henüz yeni bir sürüm olarak yayınlanmamış değişiklikler.

### Documentation

- README dokümantasyonu kapsamlı şekilde geliştirildi.
- Kurulum adımları ayrıntılandırıldı.
- SteelSeries GG güncellemeleri sonrası yapılması gerekenler açıklandı.
- Sürüm uyumluluğu hakkında bilgi eklendi.
- Hata bildirim yönergeleri geliştirildi.
- Çeviri önerileri için açıklamalar eklendi.
- Katkıda bulunma süreci README içerisinde açıklandı.
- `CONTRIBUTING.md` eklendi.
- `SECURITY.md` eklendi.
- `CHANGELOG.md` eklendi.
- Projenin SteelSeries ile resmi bir bağlantısı olmadığını belirten disclaimer eklendi.
- Resmi GitHub Releases bağlantıları belirgin hale getirildi.
- Üçüncü taraf dağıtımlarına ilişkin güvenlik uyarıları eklendi.

### Planned

- Yeni SteelSeries GG sürümleri için uyumluluk kontrolleri
- Eksik çevirilerin tamamlanması
- Hatalı veya tutarsız çevirilerin düzeltilmesi
- Yeni SteelSeries GG arayüz metinlerinin Türkçeleştirilmesi
- Topluluk tarafından bildirilen sorunların değerlendirilmesi
- Kurulum sürecinin daha kolay hale getirilmesi
- Dokümantasyonun geliştirilmesi
- Yeni sürümler için değişiklik kayıtlarının güncellenmesi

---

## [1.0.0]

İlk genel yayın.

### Added

- SteelSeries GG için kapsamlı Türkçe yerelleştirme desteği
- Engine arayüz çevirileri
- Sonar arayüz çevirileri
- Prism arayüz çevirileri
- Moments arayüz çevirileri
- Aim Tools çevirileri
- Cihaz ayarları çevirileri
- Firmware ekranı çevirileri
- Bildirim metinlerinin Türkçeleştirilmesi
- Hata mesajlarının Türkçeleştirilmesi
- Genel SteelSeries GG arayüz çevirileri
- Çeşitli cihaz ve yapılandırma ekranlarının Türkçeleştirilmesi
- Almanca (`de`) locale sistemi üzerinden Türkçe arayüz desteği
- GitHub Releases üzerinden sürüm dağıtımı
- İlk kurulum yönergeleri

### Release

İlk yayınlanan sürüm:

```text
v1.0.0
```

En güncel sürüme aşağıdaki bağlantıdan ulaşılabilir:

https://github.com/osmanilcektu/steelseries-gg-turkce-yama/releases/latest

Tüm yayınlanan sürümler:

https://github.com/osmanilcektu/steelseries-gg-turkce-yama/releases

---

## Sürüm Numaralandırması

Proje sürümleri mümkün olduğunca aşağıdaki yapıyı takip eder:

```text
vMAJOR.MINOR.PATCH
```

Örnek:

```text
v1.0.0
v1.0.1
v1.1.0
v2.0.0
```

### MAJOR

Yamanın yapısında veya çalışma yönteminde geriye dönük uyumluluğu etkileyebilecek büyük değişiklikler.

Örnek:

```text
v1.x.x → v2.0.0
```

### MINOR

Yeni özellikler, yeni SteelSeries GG bölümleri veya önemli yeni çeviri kapsamlarının eklenmesi.

Örnek:

```text
v1.0.0 → v1.1.0
```

### PATCH

Küçük çeviri düzeltmeleri, yazım hataları, küçük uyumluluk iyileştirmeleri ve dokümantasyon düzeltmeleri.

Örnek:

```text
v1.0.0 → v1.0.1
```

---

## Değişiklik Kategorileri

Yeni sürümlerde mümkün olduğunca aşağıdaki kategoriler kullanılacaktır.

### Added

Yeni özellikler, yeni çeviriler veya yeni desteklenen bölümler.

### Changed

Mevcut davranışlarda veya çevirilerde yapılan değişiklikler.

### Fixed

Hatalı çevirilerin, uyumluluk sorunlarının veya diğer problemlerin düzeltilmesi.

### Removed

Artık kullanılmayan veya kaldırılan içerikler.

### Documentation

README, CONTRIBUTING, SECURITY veya diğer dokümantasyon değişiklikleri.

### Security

Güvenlik ile ilgili değişiklikler veya düzeltmeler.

---

## SteelSeries GG Uyumluluğu

SteelSeries GG aktif olarak geliştirilen bir uygulamadır.

SteelSeries tarafından yayınlanan güncellemeler:

- Yeni çeviri anahtarları ekleyebilir.
- Mevcut çeviri anahtarlarını değiştirebilir.
- Bazı locale dosyalarının yapısını değiştirebilir.
- Dosya yollarını değiştirebilir.
- Mevcut yamanın bazı bölümlerini geçici olarak uyumsuz hale getirebilir.

Bu nedenle her yama sürümünün gelecekte yayınlanacak tüm SteelSeries GG sürümleriyle tamamen uyumlu çalışacağı garanti edilmez.

Yeni SteelSeries GG sürümleri sonrasında ortaya çıkan uyumluluk sorunları sonraki yama sürümlerinde giderilmeye çalışılacaktır.

---

## Hata ve Çeviri Bildirimleri

Eksik veya hatalı bir çeviri fark ederseniz GitHub Issues üzerinden bildirim oluşturabilirsiniz:

https://github.com/osmanilcektu/steelseries-gg-turkce-yama/issues

Bildirim oluştururken mümkünse aşağıdaki bilgileri ekleyin:

- SteelSeries GG sürümü
- Türkçe yama sürümü
- Sorunun bulunduğu bölüm
- Mevcut metin
- Önerilen metin
- Ekran görüntüsü
- Sorunun nasıl tekrarlandığı

---

## Katkılar

Topluluk katkıları kabul edilmektedir.

Katkıda bulunma yönergeleri:

[CONTRIBUTING.md](CONTRIBUTING.md)

Katkılar şu alanlarda yapılabilir:

- Eksik çevirilerin tamamlanması
- Hatalı çevirilerin düzeltilmesi
- Daha anlaşılır Türkçe karşılıkların önerilmesi
- Yeni SteelSeries GG sürümlerinin kontrol edilmesi
- Yeni çeviri anahtarlarının eklenmesi
- Uyumluluk sorunlarının giderilmesi
- Kurulum dokümantasyonunun geliştirilmesi
- README ve diğer proje belgelerinin geliştirilmesi

---

## Güvenlik

Güvenlik politikası:

[SECURITY.md](SECURITY.md)

Yama paketlerinin yalnızca bu repository'nin resmi GitHub Releases bölümünden indirilmesi önerilir.

Üçüncü taraf sitelerde yeniden paketlenmiş veya değiştirilmiş sürümlerin güvenliği ve bütünlüğü bu proje tarafından garanti edilmez.

---

## Disclaimer

This is an unofficial community project and is not affiliated with, endorsed by, or sponsored by SteelSeries.

SteelSeries, SteelSeries GG, and related trademarks belong to their respective owners.

This repository provides an independent Turkish localization intended to improve accessibility for Turkish-speaking users.

---

## Maintainer

**Osman İlçektuğ**

GitHub:  
https://github.com/osmanilcektu

Website:  
https://osmanilcektu.com

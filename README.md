# Google Fonts Utility Framework

Tailwind ve Bootstrap tarzı sınıf tabanlı mimari kullanarak, yüzlerce Google Font'unu projelerinize yalnızca birer CSS sınıfı (`class`) ekleyerek anında entegre etmenizi sağlayan pratik bir utility (yardımcı) framework.

## Özellikler

* **Sınıf Tabanlı Kolay Kullanım:** Uzun `@import` veya `<link>` kalabalığıyla uğraşmadan, doğrudan `.font-*` sınıflarıyla yazı tiplerini yönetin.
* **Devasa Font Arşivi:** `Smokum`, `Poppins`, `Playfair Display`, `Fira Code` ve binlerce farklı Google Font seçeneği.
* **Modern Arayüz Örneği:** Koyu tema (dark mode) odaklı, şık kart tasarımlarına sahip örnek bir `index.html` vitrini.

## Proje Yapısı

```text
├── my-fonts-utility.css   # Binlerce font tanımını içeren ana CSS utility dosyası
└── index.html             # Framework'ün nasıl kullanıldığını gösteren örnek arayüz
Kullanım
Projeyi bilgisayarınıza klonlayın veya indirin.

my-fonts-utility.css dosyasını kendi HTML dosyanızın <head> kısmına dahil edin:

HTML
<link rel="stylesheet" href="my-fonts-utility.css">
İstediğiniz elementi class="font-[font-adi]" şeklinde dilediğiniz fontla özelleştirin:

HTML
<h1 class="font-poppins">Bu metin Poppins fontuyla yazıldı!</h1>
Lisans
Bu proje tamamen açık kaynaklıdır ve dilediğiniz gibi geliştirip projelerinizde kullanabilirsiniz.

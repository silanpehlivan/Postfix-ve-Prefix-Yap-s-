<div align="center">

# Postfix & Prefix

**Matematiksel ifade dönüşümü**

![C#](https://img.shields.io/badge/C%23-2563eb?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-0891b2?style=flat-square)
[![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)](LICENSE)

Infix ifadeleri postfix ve prefix biçimlerine dönüştüren, postfix ifadeleri değerlendiren konsol uygulaması.

</div>

---

## Öne Çıkanlar

- Yığın tabanlı ifade dönüşümü
- Operatör önceliğinin yönetimi
- Postfix ifadelerin sayısal değerlendirilmesi

## Teknolojiler

C# · Stack

<details>
<summary><strong>Kurulum, kullanım ve teknik ayrıntılar</strong></summary>

Bu proje, infix ifadelerin **postfix** ve **prefix** gösterimlerine dönüştürülmesini ve postfix ifadelerin hesaplanmasını sağlayan C# implementasyonlarını içermektedir. Veri yapıları derslerinde sıkça kullanılan bu konu, **yığın (stack)** veri yapısı ile ele alınmıştır.

---

## Özellikler

- **Infix → Postfix Dönüşümü:** Orta ek gösterimi son ek gösterimine çevirir  
- **Infix → Prefix Dönüşümü:** Orta ek gösterimi ön ek gösterimine çevirir  
- **Postfix Hesaplama:** Postfix ifadelerin sayısal sonucunu hesaplar  
- **Operatör Önceliği:** `+`, `-`, `*`, `/`, `^` işleçlerinin önceliğini dikkate alır  
- **Stack Kullanımı:** `Stack<char>` ve `Stack<int>` veri yapıları ile işlem yapılır  

---

## Teknik Detaylar

- **Dil:** C#  
- **Veri Yapısı:** Stack (Yığın)  
- **Algoritmalar:**  
  - Infix → Postfix dönüşüm algoritması  
  - Infix → Prefix dönüşüm algoritması  
  - Postfix değerlendirme algoritması  

---

## Kazanımlar

- Yığın veri yapısını etkin kullanma  
- Matematiksel ifade dönüşümlerini anlama  
- Algoritmik düşünme becerisi geliştirme  
- Operatör önceliği mantığını öğrenme  
- İfade çözümleme algoritmalarını kavrama  

---

## Kurulum

1.  Projeyi klonlayın veya ZIP olarak indirin  
2.  Proje klasörüne gidin  
3.  Visual Studio ile `.sln` dosyasını açın  
4.  Projeyi derleyip çalıştırın  

---

## Kullanım

Program çalıştırıldığında:

- Infix ifade postfix’e dönüştürülür  
- Infix ifade prefix’e dönüştürülür  
- Postfix ifade hesaplanarak sonuç ekrana yazdırılır  

---

## Proje Yapısı

- App.config  
- LICENSE  
- Program.cs  
- Ödev_5.csproj  
- Ödev_5.sln  
- README.md  
- Properties klasörü  

---

## Katkıda Bulunma

Katkılarınız memnuniyetle karşılanır. Hata bildirimi veya yeni özellik önerileri için issue açabilir veya pull request gönderebilirsiniz.

---


</details>

---

<div align="center">

**© 2024 Şilan PEHLİVAN**

Bu proje MIT lisansı kapsamında sunulmaktadır. Kullanım ve dağıtım koşulları: [LICENSE](LICENSE).

</div>

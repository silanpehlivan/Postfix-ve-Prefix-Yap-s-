<div align="center">

# Postfix & Prefix

### İfadeyi dönüştür, işlem sırasını çöz.

![C#](https://img.shields.io/badge/C%23-2563eb?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-0891b2?style=for-the-badge)
[![MIT](https://img.shields.io/badge/MIT-16a34a?style=for-the-badge)](LICENSE)

Infix ifadeleri postfix ve prefix biçimlerine dönüştüren, postfix ifadeleri değerlendiren konsol uygulaması.

**Matematiksel ifade dönüşümü**

[Projeyi keşfet](https://github.com/silanpehlivan/Postfix-ve-Prefix-Yap-s-/tree/master) · [Kurulum ve ayrıntılar](#projeyi-çalıştırmak-ve-incelemek)

</div>

---

## İçeride neler var?

- **01** · Yığın tabanlı ifade dönüşümü
- **02** · Operatör önceliğinin yönetimi
- **03** · Postfix ifadelerin sayısal değerlendirilmesi

## Projeyi çalıştırmak ve incelemek

<details>
<summary><strong>Kurulum, kod yapısı ve teknik notları aç</strong></summary>

## Öne Çıkanlar

- Yığın tabanlı ifade dönüşümü
- Operatör önceliğinin yönetimi
- Postfix ifadelerin sayısal değerlendirilmesi

## Teknolojiler

C# · Stack

### Teknik yaklaşım

Stack<char> ile operatör önceliği yönetilir; prefix dönüşümü ters çevirme ve parantez değişimiyle elde edilir. Stack<int> postfix değerlendirmesinde operandları tutar.

### Kodu incelemeye başlayın

- [Program.cs](Program.cs)

### Kapsam ve sınırlar

İşleme karakter bazlıdır; çok basamaklı sayılar ve kapsamlı sözdizimi doğrulaması için ayrı bir tokenizer/parser gerekir.



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

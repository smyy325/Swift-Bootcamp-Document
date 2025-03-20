 # SwiftUI Bootcamp - Document

## Day 1

### Değişkenler
- Değişkenler hafızada geçici olarak saklanan değerleri temsil eder.
- Swift dilinde değişken için *tür belirtmemize* gerek yoktur. <br></br>
**NOT** -> Değişkenler kalıcı değildir.<br></br>
**NOT** -> Swift dilinde *;* yoktur. Ama ; koyarsanız bile problem olmaz hata almazsınız. Eğer tek satırda iki farklı kod yazmak istersek mecburen ; koymalıyız.
```swift
var yas : Int = 34 ; print(yas)
```

#### Değişken Oluşturma
Değişken Belirteci -> Değişken Adı -> Atama Operatörür -> Değişken Değeri <br></br>
*Örnek:* var yas =34

#### Tür Belirterek Değişken Oluşturma
Değişken Belirteci -> Değişken Adı -> Tür Belirteci -> Değişken Türü -> Atama Operatörü -> Değişken Değeri <br></br>
*Örnek:* var yas : Int = 33

#### Data Tipleri
-> **Tam Sayılar** <br></br>
*Int:* 0 dahil pozitif ve negatif sayılar <br></br>
*UInt:* 0 dahil pozitif sayılar <br></br>
-> **Ondalıklı Sayılar**<br></br>
*Double*<br></br>
*Float*<br></br>
-> **Metinsel İfadeler**<br></br>
*String:* Yazılar <br></br>
*Character:* Harfler <br></br>
-> **Mantıksal İfadeler**<br></br>
*Bool:* True veya False <br></br>

#### Literals
Literals değişkenler için kullanılan değerlerin nasıl yazılması gerektiğini temsil eder.<br></br>
*Örnek:* 
- "Ahmet" //String
- 18 //Int
- 1.78 // Double
- "A" //Character

#### Değişkenlere İsim Verme
- Büyük küçük harf farkı vardır.
- Rakamla başlayamaz.
- @, $ ve % değişken içerisinde kullanılmaz.

#### White Space - Beyaz Boşluk
Kodlama yaparken daha düzenli görünmesi için Swift boşluk bırakmamızı istemektedir.

#### print() Metdou ile Çıktı Alma
Diğer diller gibi print ve println ayrımı yoktur. Varsayılan olarak println gibi çalışır. Yani alt alta yazar. <br></br>
*Örnek:* 
- print("Merhaba") // Merhaba
- print(1.0, 2.0, 3.0) // 1.0 2.0 3.0
- print(1.0, 2.0, 3.0, separator: "-") // 1.0-2.0-3.0 <br></br>
separator ifadelerin aralarına istenilen ifadeyi yerleştirmemize yarar.

#### Değişkenleri Yazdırma
String ifade içine *\()* ifadesi kullanılarak çıktıya değişken eklenebilir.
```swift
var ad = "Sümeyye"
var yil = 11
print("\(ad) Manisada \(yil) yıldır yaşamaktadır.")
```
Sümeyye Manisada 11 yıldır yaşamaktadır.<br></br>
**NOT** -> Oluşturduğunuz değişkene farklı türde değişken atayamazsınız.<br></br>
**Not** -> Süslü parantez *{}* bizim kapsamımızı belirler. Değişkenin ulaşılabilirliği buna bağlıdır.

#### Constant - Sabitler
*let*, sabitler içerisine bir kere veri atıldığında bir daha değiştiremeyceğimiz yapılardır. let olan değişkene daha sonra değer atanmaz.

#### Kaçış Karakterleri

## Değişkenler

Merhaba. Bu ilk yazıda C dilindeki değişkenler hakkında bilgi vereceğim. İlk önce değişken nedir ve nasıl tanımlanırla başlayalım. Değişken, adı üstünde, değişebilen değer demektir. C'de değişkenleri `degiskenTipi degiskenAdi = degiskenDegeri` şeklinde tanımlarız. Mesela, `int a = 23`, `char c = 'b'`, `float d = 3.1` gibi. Değişkenleri isimlendirirken uyman gereken bazı kurallar vardır. Mesela değişkenin adının ilk karakteri sayı olamaz. Değişkeninde Türkçe karakter kullanamazsın, gibi.

### Değişken Türleri

Başlangıç aşamasında bilmen gereken 4 değişken türü var: `int`, `char`, `float` ve `double`.

1. ### int:

   Integer yani tam sayı manasına gelir: 1, 2, 3, 23, 31, -190, 423 gibi. Maksimum 2147483647, minimum -2147483647 değerini alır. Format belirteci `%d`'dir.
   Ekrana yazdırmak için `printf("%d", 23)` şeklinde kullanırsın. Boyutu bilgisayar mimarisine göre değişir ve 2 ya da 4 byte olur.

2. ### char:

   Char yani karakter manasına gelir. Ekrana yazılan her şey birer karakterdir. Maksimum 128, minimum -127 değerini alır. Format belirteci `%c`'dir. Ekrana yazdırmak için `printf("%c", 'b')` şeklinde kullanırsın. Boyutu 1 byte'tır.

3. ### float

   Kayan yani ondalıklı sayı manasına gelir. Maksimum 3.40282e+38, minimum 1.17549e-38 değerini alır. Format belirteci `%f`'dir. Ekrana yazdırmak için `printf("%f", 2.3)` şeklinde kullanırsın. Boyutu 4 byte'tır.

4. ### double
   Temelde float'la aynı olmakla beraber, depolayabileceği maksimum sayı büyüklüğü float'ın iki katıdır. Boyutu 8 byte'tır.

### Sabit (`constant`) Değişkenler

Değerinin ileride değişmeyeceğinden emin olduğumuz değişkenleri oluştururken kullanırız. Örneğin, `const int uzunluk = 20;` ya da `const float carpan = 3.1;` gibi.

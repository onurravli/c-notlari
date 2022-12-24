## Değişkenler ve Veri Türleri

Değerinin değişebildiği, içinde çeşitli tipte veri saklanan birimlere değişken denir. C'de değişken tanımlamak için `degiskenTipi degiskenAdi = degiskenDegeri` şeklinde bir söz dizimi kullanılır. Örneğin `int yas = 18;` ya da `char* ad = "beyza"` gibi.

### Veri Türleri

C'de temel olarak 4 tip veri vardır: integer (tam sayı), float (ondalıklı sayı), double (ondalıklı sayı) ve char (karakter).

1. Integer: Tam sayıları saklamak için kullanılan veri tipidir. Minimum -2147483647 ve maksimum 2147483647 değerini alır. Format belirteci `%d`'dir. Boyutu bilgisayar mimarisine göre değişir ve 2 ya da 4 byte olur.

2. Float: Floating kelimesinden gelir. Ondalıklı sayıları saklamak için kullanılan veri tipidir. Minimum 1.17549e-38 ve maksimum 3.40282e+38 değerini alır. Format belirteci `%f`'dir. Boyutu 4 byte'tır.

3. Double: Float ile hemen hemen aynıdır, tek fark, boyutunun 8 byte olmasıdır.

4. Char: Ekrana yazdırılan her şey (rakamlar, semboller, harfler vs.) birer char, yani karakterdir. Minimum -127, maksimum 128 değerini alır. Format belirteci `%c`'dir. Boyutu 1 byte'tır.

### Sabit (`constant`) Değişkenler

Değerinin ileride değişmeyeceğinden emin olduğumuz değişkenleri oluştururken kullanırız. Örneğin, `const int uzunluk = 20;` ya da `const float carpan = 3.1;` gibi.

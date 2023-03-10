## Fonksiyonlar

Tıpkı matematikte de olduğu gibi, C'de de fonksiyonlar vardır. Fonksiyonları, bir veya birden fazla işlemi tek seferde tanımlamamıza olanak sağlayan kod bileşenleridir.

### Fonksiyon Tanımlama

Fonksiyonlar bir değer döndürebildikleri gibi, herhangi bir değer döndürmeden de kullanılabilirler. Eğer fonksiyon herhangi bir değer döndürecekse, yani herhangi bir değer **`return`** etmeyecekse, fonksiyonu tanımlarken `int`, `double`, `char` gibi bir veri tipiyle tanımlamamız gerekir. Eğer herhangi bir değer döndürmeyeceksek de fonksiyonu `void` kelimesiyle tanımlamamız gerekir.

```c
int degerDondurenFonksiyon() {
    // Bazi islemler
    return degiskenAdi;
}
```

ya da

```c
void degerDondurmeyenFonksiyon() {
    // Bazi islemler
}
```

gibi.

### Fonksiyon Parametreleri
Bazen, bir fonksiyonu kullanırken, birtakım parametreleri kullanmamız gerekir. Buna passing argument adı verilir.

```c
int kare(int sayi) {
    return sayi * sayi;
}
```

gibi.


### Fonksiyon Çağırma

Daha önceden tanımladığımız bir fonksiyonu çağırmak için `fonksiyonAdi();` şeklinde bir kullanım yapmamız gerekir. Unutulmamalıdır ki, fonksiyon bir değer alıyor ve biz de fonksiyonu çağırırken herhangi bir değer göndermiyorsak kodumuz hata verecektir. Örneğin `kare` fonksiyonu bir değer alıyor, `kare(23);` şeklinde kullanılmalıdır.
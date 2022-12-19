## If-Else yapısı

C'de kontrol mekanizmalarının başında `if` ve `else` yapısı gelir.

### 1. If yapısı

Bunu kod üstünden anlatmakta bir beis görmüyorum:

```c++
if(yas < 18) {
  printf("Giris yapamazsiniz.");
}
```

Bu kod bloğu, eğer `yas` değişkeni 18'den küçükse `Giris yapamazsiniz.` yazmak için kullanılıyor. Tamam, yaş 18'den küçükse giremiyor da, 18'e eşit ya da 18'den küçükse ne yapılacak? İşte bu durumda `else` kullanmamız gerekiyor.

### 1. Else yapısı

Yukarıdaki kodu aynen kopyalıyorum:

```c++
if(yas < 18) {
  printf("Giris yapamazsiniz.");
}
```

Ve bir ekleme yapıyorum:

```c++
if(yas < 18) { // Yaş, 18'den küçükse
  printf("Giris yapamazsiniz.");
} else { // Yaş, 18'e eşitse ya da 18'den büyükse
  printf("Giris yapabilirsiniz.");
}
```

Gördüğün gibi 18'den küçük olma durumunu ve diğer durumu ele almış olduk. Ama bir de tam 18'e eşitse ne yapmalıydık? İşte burada da `else if` kullanmamız gerekiyor. Bu örnekte de yaş 18'den küçükse giremesin, 18'e eşitse tam sınırdan girsin, 18'den büyükse sorunsuzca girebilsin.

```c++
if(yas < 18) { // Yaş, 18'den küçükse
  printf("Giris yapamazsiniz.");
} else if(yas == 18) { // Yaş, 18'e eşitse
  printf("Tam sınırdan girdiniz, tebrikler.");
} else {
  printf("Giris yapabilirsiniz."); // Yaş 18'den büyükse
}
```

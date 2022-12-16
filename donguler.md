## Döngüler

C'de tekrarlı işlemleri daha kolay gerçekleştirebilmek için döngüleri kullanırız. For, while, do-while olmak üzere 3 tip döngü vardır.

### 1. For Döngüsü

For döngüsünde, bir iteratör belirlenir ve bu iteratörün belirli aralıklarda artıp azalmasıyla döngü gerçekleştirilir. Örneğin 0 ile 100 arasında bir döngü kurmak için,

```c
int i;
for(i = 0; i<100; i++) {
  // ...
}
```

şeklinde bir tanımlama yapmamız yeterlidir. Bu döngüde iteratör i, 0'dan başlayıp 100'e kadar (**100 hariç!**) artacak ve bu esnada gerekli işlemleri gerçekleştireceğiz.

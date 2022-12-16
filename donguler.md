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

### 2. While Döngüsü

While döngüsü de, İngilizcesinden anlayabileceğimiz şeklinde, iken manasına gelen bir döngüdür. Belirttiğimiz şart doğru olduğu müddetçe istediğimiz işlemler gerçekleştirilir. Örneğin sayımız 10'dan küçük olduğu müddetçe sayıları ekrana yazan kod, şu şekildedir:

```c
int i=0;
while(i<10) {
  printf("%d\n", i);
  i++; // UNUTULMAMALI !!
}
```

Burada önemli olan nokta, iteratör i'yi döngü içerisinde artırmamız gerektiğidir. Aksi halde i hep 10'dan küçük olacaği için sonsuz bir döngü meydana gelecektir. Bu kodun çıktısı şu şekilde olacaktır:

```
0
1
2
3
4
5
6
7
8
9
```

### 3. Do-While Döngüsü

Temelde while döngüsü ile aynı olan do-while döngüsünün tek farkı, while döngüsünde gerçekleştirilen işlemin **en az 1 kere** yapılmasıdır. Yani döngü şartı doğru olsun olmasın, döngü içerisinde verilen işlem en az 1 kere gerçekleştirilir.

```c
int i=0;
do {
  printf("%d\n", i);
  i++;
} while(i < 10);
```

Bu kodun çıktısı da şu şekilde olacaktır:

```
0
1
2
3
4
5
6
7
8
9
```

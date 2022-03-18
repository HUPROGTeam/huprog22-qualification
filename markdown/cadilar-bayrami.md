<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Cadılar Bayramı
Cadılar Bayramında küçük çocuklar kapı kapı dolaşıp ev sahiplerine "şaka mı şeker mi" diye sorar. Ev sahibi eğer şakayı seçerse çocuklar korkunç kıyafetleri ile komiklik yaparlar.

Cadılar Bayramında evini ziyarete gelecek $x$ sayıda çocuk için Arda evinin bir köşesinde $n$ adet şeker bulundurmaktadır. Arda'yı ziyarete gelen çocuklar grup halinde takılmaktadır.Yani Arda'nın zili her çalındığında kapısında $x$ sayıda çocuk bitmektedir. Şeker yemeyi sevmeyen Arda elindeki bütün şekerleri çocuklara dağıtmak istemektedir. Kendisini ziyarete gelen her çocuğun eşit sayıda şekere sahip olmasını isteyen Arda eğer şekerleri adil bir şekilde dağıtıp bitirmek mümkün değilse hiçbir çocuğa şeker vermeyecektir.

## Input Format
-   İlk satırda Arda'yı ziyarete gelecek çocuk sayısı verilmektedir ($x$).
-   İkinci satırdaki $x$ adet sayı herbir çocuğun Arda'yı ziyarete gelmeden önce sahip oldukları şeker sayılarını vermektedir.
-   Üçüncü satırda ise Arda'nın sahip olduğu toplam şeker sayısı verilmektedir ($n$).

## Output Format
Arda'nın şekerlerini adil bir şekilde dağıtıp bitirmesi mümkünse 1, mümkün değilse 0 yazdırın.

## Constraints
-   $1 \le x \le 10$
-   $1 \le n \le 100000$

## Sample Input 1
```
3
5 3 2
8
```
## Sample Output 1
```
1
```

## Explanation 1
Birinci çocuğa 1, ikinci çocuğa 3, üçüncü çocuğa da 4 şeker verildiğinde çocuklarının elindeki şeker sayıları eşit olmakta ve Arda elindeki şekerlerden kurtulmaktadır.

## Sample Input 2
```
3
10 20 15
14
```

## Sample Output 2
```
0
```
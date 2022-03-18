<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# HUPROG Sayısı
_HUPROG_ ilk kez 2016 yılında _Bilge Çimen_ tarafından düzenlenmiştir. Bilge, bu tarihin önemi adına **2** ve **6** rakamlarını _HUPROG_ rakamları olarak kabul etmiştir.

2022 _HUPROG_ ekibinden Berat ve Şura _HUPROG_ rakamlarını çok sevdiklerinden onunla ilgili bir oyun kurup oynamaya karar verirler. Bu oyunda kendi aralarında bir fonksiyon uydururlar ve buna da _M(x)_ fonksiyonu derler. _M(x)_ fonksiyonu içine girdi olarak bir tam sayı alır ve çıktı olarak da bu sayıda yer alan kaç tane _HUPROG_ rakamı olduğu bilgisini verir.

**Örneğin; M(123486628) fonksiyonu 4 çıktısını verir çünkü iki tane '2' iki tane de '6' yani toplam dört HUPROG rakamı yer almaktadır.**

Oyunda karar verdikleri bir **A** sayısından başlayarak **(A+T)**'ye kadar saydıklarında _(yani A , A+1 , A+2 ... A+T-1 (A+T dahil değil))_, elde ettikleri her sayıyı sırayla _M(x)_ fonksiyonuna sokmaktadırlar ve bu sayıları sırasıyla not etmektedirler. Oyunda bulmaları gereken bir **B** sayısı vardır ve **B** sayısı öyle bir sayı olmalı ki tam olarak şu özellikleri sağlamalı:

-   **B**'den **(B+T)**'ye kadar olan sayıların _M(x)_ çıktısı ile **A**'dan **(A+T)**'ye kadar olan sayıların _M(x)_ çıktısı aynı sırada ve aynı değerde olmalı,
-   **B** sayısı **A**'dan büyük ve yukarıdaki özelliği sağlayan en küçük sayı olmalı.

**B** sayısını ilk bulan oyunu kazanacaktır ancak Şura çok yavaş saydığı için sizin yardımınıza ihtiyacı vardır. Şura'ya yardımcı olur musunuz?

## Input Format
Sırasıyla _A_ ve _T_ sayıları verilir.

## Output Format
_B_ sayısı çıktı olarak verilir.

## Constraints
$1 \leq A, T \leq 10^9$

## Sample Input 1
```
6 2
```

## Sample Output 1
```
12
```

## Explanation 1

Girdilerimiz 6 ve 2 iken başlangıç sayımız 6'dır. 6 ve 7 için M(6)=1, M(7)=0. M fonksiyonuna verilecek sayılar için 1-0 çıktılarını sağlayacak en küçük B sayısı 12'dir. Çünkü M(12)=1, M(13)=0'dır. 12 den küçük ve 6'dan büyük hiçbir sayı bu koşulu sağlamaz.
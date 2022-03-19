<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Serhat ve En Yakın Arkadaşı Selim
Serhat, farklı bir şehirde yaşayan ve aralarında $N$ birim mesafe olan arkadaşı Selim ile birlikte algoritma çalışmak istemektedir ancak artan bilet fiyatları yüzünden bir türlü bir araya gelememektedirler. Lakin bir gün Serhat'ın bu çaresiz halini gören biri çıkıp ona bir teklif sunuyor. Özel güçlere sahip bu kişi herhangi bir eline küçük bir oyuncak alıyor ve Serhat'ın, oyuncağın hangi elinde olduğunu tahmin etmesini istiyor. Eğer Serhat, oyuncağın hangi elinde bulunduğunu doğru bilirse, bu kişi özel güçlerini kullanarak Serhat ile birlikte 2 birim mesafe kadar *ileriye doğru* ışınlanacağını söylüyor ancak şayet bilemezse onunla yalnızca 1 birim mesafe kadar *ileriye doğru* ışınlanacağını söylüyor. Bu kişinin bu işlemi her uçuş bittiğinde tekrarladığını varsayarsak, Serhat ile Selim'in buluşma olasılığı nedir?

## Input Format
İlk ve tek satırda yalnızca bir tam sayı $N$, Serhat ile Selim arasındaki mesafe veriliyor.

## Output Format
Serhat ile Selim'in buluşma olasılığını belirten bir reel sayı (real number). Yazdırırken virgülden sonra tam olarak 6 basamak olması gerekmektedir.

## Constraints
- $1 \leq t \leq 100$
- $1 \leq N \leq 10^{5}$

## Sample Input 1
```
3
```
 
## Sample Output 1
```
0.625000
```

## Explanation 1
İhtimalleri goz onunde bulundurursak:

Oyuncağın hangi elinde olduğunu doğru bilirse 2, bilemezse 1 adım gittiğini varsayarsak:
- 1-1-1 ( 3 kez bilemez ve 1-1-1 adım gidebilir )
- 1-2 ( 1'incisinde bilemez, 2'ncisinde bilir )
- 2-1 ( 1'incisinde bilir, 2'cisinde bilemez )

Hangi elinde olduğunu doğru bilme olasılığı $1/2$ ve bilememe olasılığı da $1/2$ olduğu için

Tam olarak 3. noktada duran arkadaşına ulaşma olasılığı : $$( 0.5 * 0.5 * 0.5 )+ ( 0.5 * 0.5 ) + ( 0.5 * 0.5 ) = 0.125000 + 0.250000 + 0.250000 = 0.625000$$

## Sample Input 2
```
2
3
8
````

## Sample Output 2
```
0.625000
0.667969
```
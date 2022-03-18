<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>           

# Yonge Caddesi
Dünyanın en uzun caddesi Kanada'nın Toronto kentindeki Yonge Caddesi'dir. Bu cadde üzerindeki mağazalar türlerine göre sayılarla temsil edilmektedir. Toronto Belediye Başkanı Oğuzhan, caddenin daha düzenli görünmesi için yan yana duran farklı türdeki mağazalardan bazılarını yıkıp aynı tür mağazaları bir araya getirmek istiyor. Oğuzhan'ın ayrılan bütçeye göre yıkabileceği maksimum mağaza sayısı sınırlıdır ve bu sayıyı aşamaz.

## Input Format
$S$: Caddedeki bitişik mağaza sayısı.
$T$: Mağaza türünü temsil eden maksimum sayı.
$D$: Oğuzhan'ın bütçeye göre yıkabileceği maksimum mağaza sayısı.

$İlk$ $satır:$
$S$, $T$ ve $D$.
$İkinci$ $satır:$
$1$ ile $T$ arasında $S$ tamsayıları.

## Output Format
Yan yana birleştirilebilen aynı türden maksimum mağaza sayısı.

## Constraints
$1 \le S \le 10^5$

$1 \le T \le 1000$

$0 \le D \le S$

## Sample Input 1
```
3 2 0
2 1 2
```

## Sample Output 1
```
1
```

## Explanation 1
$D$ sıfır yani bütçe hiçbir mağazayı yıkmaya yetmedi.

## Sample Input 2
```
4 3 1
3 2 3 1
```

## Sample Output 2
```
2
```

## Explanation 2
Oğuzhan 1. indeksteki mağazayı yıktı ve sokaktaki mağazaların yeni görünümü 3 3 1 şeklinde oldu. Yani 2 aynı tip mağaza birleşti.

## Sample Input 3
```
5 4 2
1 1 3 1 3
```
## Sample Output 3
```
3
```
## Explanation 3
Oğuzhan 2. indeksteki mağazayı yıktı ve sokaktaki mağazaların yeni görünümü 1 1 1 3 şeklinde oldu. Yani 3 aynı tip mağaza birleşti.
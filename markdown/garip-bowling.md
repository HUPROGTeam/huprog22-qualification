<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Garip Bowling
Hacettepe Üniversitesi 55. Geleneksel Bowling Turnuvasında finale kalan Bora ve Yaşar, turnuva şampiyonunu belirlemek için normalden farklı bir tür bowling oynamaya karar verirler.  
Oynayacakları bu oyunda normalden farklı bir şekilde, labutlar üçgensel yerine karesel şekilde dizilecektir.

Karenin bir kenarı _**n**_'dir ve oyun, _**nxn**_ bir oyun sahasında oynanacaktır. Atışlar, karenin istenilen kenarından yapılacaktır ve atış yönleri sırasıyla:

-   0 -> _Doğu_'dan _Batı_'ya
-   1 -> _Güney_'den _Kuzey_'e
-   2 -> _Batı_'dan _Doğu_'ya
-   3 -> _Kuzey_'den _Güney_'e olarak verilecektir.

Top, her zaman istenilen labuta isabet edecektir.  
Atıştan isabet alan labut, atış yönünde devrildiği yöndeki ve kendisinin çaprazındaki 2 labutu da devirecektir, yani 1 labut devrildiğinde kendisiyle beraber 3 labutu daha devirmektedir. Devrilen her labut aynı şekilde kendi arkalarındaki diğer labutları da devirecektir.  

## Input Format
İlk satır kare labut sahasının bir kenarında bulunan labut sayısını belirten integer $n$'dir.  
İkinci satır, atışın yapıldığı koordinatlar olan 2 integer $x$ ve $y$'dir. Bu interler 0-indeksli olarak verilmektedir.  
Üçüncü satır atış yönünü belirten integer $d$'dir.

## Output Format
Devrilmiş olan toplam labut sayısı.

## Constraints
$1 \le n \le 10^{4}$

## Sample Input 1
```
3
2 1
1
```

## Sample Output 1
```
7
```

## Explanation 1
![](https://imagizer.imageshack.com/img922/33/sdj1Rl.png)

1\. yönden x = 2, y = 1 labutuna atılan top kendi arkasındaki oklarla belirtilen 3 labutu devirir. Bu devrilen 3 labut da aynı şekilde kendi arkalarındaki oklarla belirtilen labutları devirir. En son toplam 7 labut devrilir.
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Still Got the Palindromes
Özgün kendini denemek için bir gitar yarışmasına katılmak istiyordur. Eskiden yazdığı sololarını yarışmada kullanabileceğini düşünmektedir ancak yarışmanın kurallarını okuduğunda garip kurallar olduğunu öğrenmiştir:

-   Solonun notaları bir harf dizisi olarak düşünüldüğünde bu dizi palindrom olmalıdır. ($s_i$ = $s_{n+1-i}$, \[1, n\] aralığındaki bütün i değerleri için)
-   $i^{th}$ nota ile $(i+k)^{th}$ nota aynı olmalıdır. ($s_i$ = $s_{i+k}$ \[1, n-k\] aralığındaki bütün i değerleri için, $k$ inputta verilecektir)

Bu kurallarla uyumlu olmayan bir solo çalan yarışmacılar yarışmadan diskalifiye olacaklardır. Özgün yarışmadan diskalifiye olmak istememektedir ve yazdığı eski soloların yeterince iyi olduğuna inanmaktadır. Sololarını uyumlu hale getirmek için minimum kaç notayı değiştirmesi gerektiğini bulunuz.

## Input Format
İlk satır $q$ tam sayısını içermektedir - test case sayısı

Her test şunları içermektedir:
-   İlk satırda iki adet $n$ ve $k$ tam sayısı — solonun uzunluğu ve açıklamada bahsedilen $k$ değeri
-   İkinci satırda $n$ uzunluğunda string — solonun notaları

## Output Format
Her test case için minimum değişiklik sayısını bastırın.

## Constraints
-   $1 \leq q \leq 10^5$
-   $1 \leq k < n \leq 2 \cdot 10^5$ ($0 \equiv n\mod{k}$, $\sum_{i=1}^{q}n_i \leq 2 \cdot 10^5$)
-   Verilen bir stringde yalnızca büyük A, B, C, D, E, F, G harfleri bulunabilir.

## Sample Input 1
```
3
6 2
FGFFGF
36 9
BCAADADEDFDBGEBDGBGBBCAABBBBCDABDBCB
21 7
BCDEAEFGAEABAEABCDEFG
```

## Sample Output 1
```
2
19
14
```

## Explanation 1
İlk test case için, verilen stringin minimum değişiklikle düzeltilmiş bir hali F**F**FF**F**F, dolayısıyla cevap 2.
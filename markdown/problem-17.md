<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Problem 17
Berat okulda ona verilen bir algoritma problemini çözmek için bir gün kafa patlattıktan sonra Yasin'e danışmaya karar verir. Verilen problemde her biri _**M**_ uzunluğunda _**N**_ tane string vardır.Berat'tan istenen ise tüm bu stringleri sıralamasıdır. Fakat bu sıralama işlemi bilindik sıralama gibi değildir. Stringleri karşılaştırırken index'i asal sayı olan karakterleri "azalan sıra"ya göre, asal sayı olmayanları ise "artan sıraya"a göre yapması isteniyor. Yasin üstün algortima yeteneklerini kullanarak bu problemi beş dakika içerisinde çözmüştür. Berat başkalarının bu soruyu ne kadar sürede çözeceğini merak ettiği için HUPROG ön elemesine koymaya karar vermiştir.


## Input Format
İlk satırda kelime sayısı olan _**N**_ ve her bir kelimenin uzunluğu olan _**M**_ verilmiştir.

Takip eden _**N**_ satırda ise bu kelimeler verilmiştir.

## Output Format
Kelimelerin sıralanmış halini satır satır yazdırınız.

Son satırda ise verilen inputa göre indexlerini yazdırınız

## Constraints
$0 \le N \le 4000$

$0 \le M \le 10000$

Kelimelerin tüm karakterleri küçük harfli karakterlerden oluşmaktadır.

## Sample Input 1
```
5 5
abcde
abcef
abdeg
aabef
abzdu
```

## Sample Output 1
```
aabef
abzdu
abdeg
abcef
abcde
4 5 3 2 1
```

## Explanation 1
abzdu ve abdeg kelimeleri üzerinden açıklamak gerekirse

0 ve 1. indexlere bakınca bir değişiklik yok. 2. index asal olduğu için descending order'a göre sıralama yapmamız gerekiyor. Bu sebepten dolayı abzdu kelimesi abdeg kelimesinden daha önce gelir.

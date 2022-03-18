<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Zero Density
Bu yıl HUPROG'un platin sponsoru olan **Zero Density** yaz stajı için başvurularını açtığını duyurmuştur. İnternette dolaşırken bu şirketin staj ilanıyla karşılaşan HUPROG takımındakiler bu staja başvurmaya karar verirler. Başvuru yaptıktan bir süre sonra ekiptekilere başvurunun kabul edilip mülakat aşamasına geçtiklerine dair bir mail gelmiştir. Bunlardan biri de HUPROG takımından **Berat**'tır. Zero Density, Berat'a mülakatta şu soruyu sormuştur :

Verilen _**S**_ stringinde kaç adet **"zero"** kelimesi oluşturulabilir (1. Açıklamaya Bakınız)?

Berat çok heyecanlı bir kişiliğe sahip olduğundan mülakatta bildiği her şeyi unutur bu yüzden _Berat_ 'a mülakatı geçmesinde yardımcı olun.

Note: Sonuçlar çok büyük olabileceğinden $10^9+7$'ye göre modunu alarak yazdırınız.

## Input Format
İlk satırda _**S**_ stringinin uzunluğu.
ikinci satırda satırda _**S**_ stringi verilecektir.

## Output Format
Verilen _**S**_ stringinde kaç adet "zero" kelimesi olduğunu yazdırınız.

## Constraints
0 < _**len(S)**_ < $8*10^7$

## Sample Input 1
```
8
ezeerroo
```
## Sample Output 1
```
8
```
###### Explanation 1

1 2 4 6

1 2 4 7

1 2 5 6

1 2 5 7

1 3 4 6

1 3 4 7

1 3 5 6

1 3 5 7

indexleriyle oluşturulabilir

## Sample Input 2
```
13
zabezerzzeroo
```
## Sample Output 2
```
20
```

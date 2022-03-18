<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Attack on Shiganshina

Shiganshina bölgesinde güneşli ve sakin bir günde ansızın bölgeyi çevreleyen duvarların yıkılması ve beraberinde meydana gelen titan saldırısı, bölgenin sakinlerinden olan Eren’i çok korkutur. Titanlar insanlardan çok daha uzun boylu ve güçlü devlerdir, bu yüzden onlara meydan okumak insanlar için çok zordur.Titanlara karşı savaşan insanlar yoğun bir askeri eğitim görmek zorundadır. Fakat bazı insanlar, farklı görüşleri sebebiyle titanların saldırılarını destekler. Bu insanlar da aynı şekilde askerlerdir, titanlar için çalışırlar. Bölgeye saldıran titanların yanlarında birkaç insan asker de bulunmakta ve saldırıya yardım etmektedir. Ancak Eren korkusuz bir gençtir, yaşadığı yeri savunmak için elinden geleni yapacaktır. Eren’in kendisine yardım etmesi için birkaç devi kontrol edebilme gücü vardır, bu sebeple gücünü kullanarak yardımını alabildiği birkaç dev ve asker arkadaşlarından oluşan bir ordu ile Shiganshina’ya saldıranlardan intikamını almaya karar verir. Şehrin meydanında, iki grup kendi savaşçıları (titan ve insan) yan yana dizili şekilde karşılıklı yerleşir ve birbirlerini yok etmeye yemin ederler. Eren bu savaşı kazanma olasılığını hesaplamak ister, bunu hesaplamak için de şöyle bir yöntem bulur: Eren kendi takımındaki her bir savaşçı için, diğer takımdaki bu savaşçıdan kısa boylu tüm savaşçıların sayısını bulmaya karar verir.
Bulduğu bu hesaplamaları ise sıralı bir şekilde tutar. 

Eren'nin hesapladığı sayı dizisini bulunuz.

## Input Format

İlk satırda diğer takımdaki $t$ ve Eren'in takımındaki $e$ savaşçı sayıları ($1\le t, e\le 10^5$)
İkinci satırda diğer takımın $t$ tane savaşçısının boyları
Üçüncü satırda Eren'in takımının $e$ tane savaşçısının boyları

## Output Format
$e$ kadar Eren'in hesapladığı sayı dizisi.

## Constraints
- $1 \le t, e \le 10^5$
- $1 \le t_i, e_i\le 10^9$

## Sample Input 1
```
6 6
94 63 9 98 69 99
17 17 85 61 71 22
```

## Sample Output 1
```
1 1 1 1 3 3 
```

## Explanation 1
Dizinin her bir elemanı Eren’in takımındaki her bir savaşçı için diğer takımda kendisinden kısa olan savaşçı sayısını gösterir.
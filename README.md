# Walmart Satış Məlumatlarının Analizi - Market Basket Analizi
![Description of Image](assets/Ekran%20şəkli%202024-11-14%20155324.png)


Bu layihədə, Walmart satış məlumatlarını **Market Basket Analizi** üzərində diqqət mərkəzində saxlayaraq analiz edirik. Məqsəd məhsul assosiasiyalarını, populyar məhsul kombinasiyalarını və satış nümunələrini həftənin günü və günün saatına əsasən təyin etməkdir. Analiz aşağıdakı üç əsas hissədən ibarətdir:

## 1. Ən Yaxşı 3 Məhsullu Kombinasiyalar

- Əsas məqsəd tez-tez birlikdə alınan məhsul cütlərini tapmaq və onları ən çox əlaqəli olan üçüncü məhsulla genişləndirməkdir. Hər məhsul üçün onun ən yaxşı cütlüyünü müəyyən etmək (məsələn, *çörək* tez-tez *süd* ilə alınır) və səbətdə ən çox birlikdə olan üçüncü məhsulu tapmaqdır (məsələn, *çörək* və *süd* ilə tez-tez *pendir* alınır).
- Bu məlumatlara əsaslanaraq, həmin cütlük və üçlüklərin eyni əməliyyatda bir yerdə olma ehtimallarını hesablayırıq.

## 2. Saatlara Görə Ən Yaxşı Məhsul Kombinasiyaları

- Günün müxtəlif saatlarında məhsul satışlarını analiz edərək hər saatda ən çox satılan üç məhsulu müəyyən edirik.
- Bu, saatlıq satış tendensiyalarını başa düşməyə və günün müxtəlif saatlarında tələbatın zirvə nöqtələrinə əsaslanaraq inventar və ya promosyonları optimallaşdırmağa imkan verir.

## 3. Həftə Günlərinə Görə Ən Yaxşı Məhsul Kombinasiyaları

- Həftənin hər günü üçün məhsul satışlarını analiz edərək həmin gün ən çox satılan üç məhsulu müəyyən edirik.
- Bu analiz həftəlik tələbat dövrlərinə uyğun olaraq inventar və promosyon planlamasını dəstəkləməyə kömək edən günlük satış nümunələrini aşkar etməyə imkan verir.

Analizin hər bir hissəsi ayrıca bir dashboard səhifəsində vizuallaşdırılacaq, bu isə satış strategiyalarını optimallaşdırmaq, müştəri təcrübəsini yaxşılaşdırmaq və inventar planlamasına dəstək olmaq üçün məlumatlara əsaslanan qərar qəbul etməyə imkan verəcək.

## Başlangıç durumu: [16,21,11,8,12,22]

###### Sorting aşamaları:

    1.       [16,21,11,8,12,22]

    2.     [16,21,11] - [8,12,22]

    3. [16,21] - [11] - [8,12] - [22]

    4.  [16] [21] [11] [8] [12] [22]

    5.    [16,21] [11] [8,12] [22]

    6.      [11,16,21] [8,12,22]

    7.       [8,11,12,16,21,22]

##### Big-O gösterimi:

Yaptığımız toplam bölme ve birleştirme sayımız 2^x = n buradan O(logn) gelir,

Her satırda yaptığımız işlem sayısı ise n yani O(n),

Toplam ise: O(nlogn) olur.

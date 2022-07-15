# Merge-Sort
---

```
Birleştirme sırlaması algoritması da denir. Parçala fethet mantığı vardır. Bundan biraz bahsedelim.
```

### Verilen Diziyi Merge Sort algoritmasına göre sıralayalım
                        [16,21,11,8,12,22]
            [16,21,11]                      [8,12,22]           1. aşama
        [16]          [21,11]          [8,12]         [22]      2. aşama
      [16]               [11,21]     [8,12]             [22]    3. aşama
          [11,16,21]                       [8,12,22]            4. aşama
          
                        [8,11,12,16,21,22]                      5. aşama
                        
     Burada neler oluyor biraz da ondan bahsedelim... 
     1. ve 2. aşamada görüldüğü gibi elimdeki diziyi PARÇALADIM.
     Elimde parçalanmış diziler kaldı. 3. aşamada da dizilerin kendi içinde bir sıralama yaptım.
        - Mesela [21,11] dizisi kendi içinde sıralayıp [11, 21] oldu.
        - Tek elemanlı diziler zaten sıralanmıştır. Çünkü eleman 1 tane olduğu için otomatik olarak sıralı olmuş oluyor.
     4. aşamada parçalanmış dizilerin bir kısmını birleştiriyorum.
     5. aşama -son aşamada- ise elimde olan 2 diziyi birleştiriyorum.
     
     Sonuç olarak PARÇALADIM ve FETHEDEREK de birleştirdim.

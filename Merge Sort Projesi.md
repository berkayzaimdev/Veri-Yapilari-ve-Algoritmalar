## [16,21,11,8,12,22] -> Merge Sort
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
### 2. Big-O gösterimini yazınız.

1.

               [16,21,11,8,12,22]                     Başlangıç Aşaması
         [16,21,11]           [8,12,22]               1. Aşama
    [16]      [21,11]        [8]     [12,22]          2. Aşama  
 [16]     [21]    [11]      [8]     [12]     [22]     3. Aşama
    [16]     [11,21]         [8]     [12,22]          4. Aşama
         [11,16,21]           [8,12,22]               5. Aşama
               [8,11,12,16,21,22]                     6. Aşama
              
2. O(n.log(n))

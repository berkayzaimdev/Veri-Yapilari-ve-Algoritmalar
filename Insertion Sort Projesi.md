# A) [22,27,16,2,18,6]
#### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
#### 2. Big-O gösterimini yazınız.
#### 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
#### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

---

1.

- [22,27,16,2,18,6] Başlangıç

- [22,27,16,2,18,6] 1. Aşama -> 27, 22'den büyük olduğu için değişen bir şey yok.

- [16,22,27,2,18,6] 2. Aşama -> 16<27 ve 16<22 olduğu için 16 ilk indise yerleşti.

- [2,16,22,27,18,6] 3. Aşama -> 2<27, 2<22, 2<16 olduğu için 2 ilk indise yerleşti.

- [2,16,18,22,27,6] 4. Aşama -> 18<27, 18<22 olduğu için 18 üçüncü indise yerleşti.

- [2,6,16,18,22,27] 5. Aşama -> 6<27, 6<22, 6<18, 6<16 olduğu için 6 ikinci indise yerleşti. 6 dizideki son eleman olduğu için sıralama tamamlanmış oldu.


2.

**Worst Case:** O(n^2)

**Average Case:** O(n^2)

**Best Case:** O(n)


3.

**Worst Case:** [27,22,18,16,6,2]

**Average Case:** [6,2,22,18,16,27]

**Best Case:** [2,6,16,18,22,27]


4.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında olacağı için Average Case kapsamına girer.

---

# B) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- [7,3,5,8,2,9,4,15,6] Başlangıç

- [**3,7**,5,8,2,9,4,15,6] 1. Aşama -> 3<7

- [3,**5,7**,8,2,9,4,15,6] 2. Aşama -> 5<7

- [3,5,**7,8**,2,9,4,15,6] 3. Aşama -> 8>7 olduğu için bir şey değişmedi.

- [**2,3**,5,7,8,9,4,15,6] 4. Aşama -> 2<3



### veri-yapilari-ve-algoritmalar-insertion-sort-proje
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje


### Proje 1
### [22,27,16,2,18,6] -> Insertion Sort
#### 1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] 		-> n

[22,27,16,2,18,6] 		-> n-1

[16,22,27,2,18,6] 		-> n-2

[2,16,22,27,18,6] 		-> n-3

[2,16,18,22,27,6] 		-> n-4

[2,6,16,18,22,27] 		-> 1

#### 2.	Big-O gösterimini yazınız.
O(n^2)

#### 3.	Time Complexity: 
Average case: Aradığımız sayının ortada olması.[2,6,(16),18,22,27] [2,6,16,(18),22,27] 

Worst case: Aradığımız sayının sonda olması.  [2,6,16,18,22,(27)] 

Best case: Aradığımız sayının dizinin en başında olması. [(2),6,16,18,22,27] 

#### 4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Aradığımız sayının ortada olması nedeniyle; Average Case. (3.maddeye referansla)



### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]		-> n

[3,7,5,8,2,9,4,15,6]		-> n-1

[3,5,7,8,2,9,4,15,6]		-> n-2

[3,5,7,8,2,9,4,15,6]		-> n-3

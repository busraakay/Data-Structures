# Patika.dev .Net Patikası Veri Yapıları ve Algoritmaları Projeleri


### <a href='#Insertion Sort Projesi'>Insertion Sort Projesi</a><br>
### <a href='#Merge Sort Projesi'>Merge Sort Projesi</a><br>
### <a href='#Binary Search Tree Projesi'>Binary Search Tree Projesi</a><br>



## <p id = 'Insertion Sort Projesi' > Insertion Sort Projesi </p> 
#### [22, 27, 16, 2, 18, 6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1. [22, 27, 16, 2, 18, 6]
2. [2, 27, 16, 22, 18, 6]
3. [2, 6, 16, 22, 18, 27]
4. [2, 6, 16, 22, 18, 27]
5. [2, 6, 16, 18, 22, 27]
```
2. Big-O gösterimini yazınız.
```
n + (n-1) + (n-2) + ... + 1 
= (n * (n + 1)) / 2
= (n^2 + n) / 2
= O(n^2)
```
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
```
Average case: O(n^2)
Worst case: O(n^2)
Best case: O(n)
```
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Average case
```
#### [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. [2, 3, 5, 8, 7, 9, 4, 14, 15, 6]
2. [2, 3, 4, 8, 7, 9, 5, 14, 15, 6]
3. [2, 3, 4, 5, 7, 9, 8, 14, 15, 6]
4. [2, 3, 4, 5, 6, 9, 8, 14, 15, 7]
```



## <p id = 'Merge Sort Projesi' > Merge Sort Projesi </p> 
#### [16, 21, 11, 8, 12, 22] -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```
[16, 21, 11, 8, 12, 22]
[16, 21, 11]  | [8, 12, 22]
[16] [21, 11] | [8, 12] [22]
[16] [11, 21] | [8, 12] [22]
[11, 16, 21]  | [8, 12, 22]
[8, 11, 12, 16, 21, 22]
```
2. Big-O gösterimini yazınız.
```
O(nlog(n))
```
## <p id = 'Binary Search Tree Projesi' > Binary Search Tree Projesi </p> 



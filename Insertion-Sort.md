# InsertionSort
[22,27,16,2,18,6]
## Soru 1: Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. 
```
1[22,16,27,2,18,6]
2[16,22,27,2,18,6]
3[16,22,2,27,18,6]
4[16,2,22,27,18,6]
5[2,16,22,27,18,6]
6[2,16,22,18,27,6]
7[2,16,18,22,27,6]
8[2,16,18,22,6,27]
9[2,16,18,6,22,27]
10[2,16,6,18,22,27]
11[2,6,16,18,22,27]

```
## Soru 2: Big-O gösterimini yazınız.
```
O(n): best case
--------------
n*(n+1)/2 
(n^2 + n) / 2
O(n^2): average- worst case
```
## Soru 3: Time Complexity
```
Worst Case: Aranan sayının sonda olması
Average Case: Aranan sayının ortada olması
Best case: Aradığımız sayının en başta olması

```
## Soru 4 : Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer
```
Average Case : 18 sayısı ortadadır.
```
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,2,8,9,4,15,6]
[3,5,2,7,8,9,4,15,6]
```
[Patika.dev](https://www.patika.dev/tr)

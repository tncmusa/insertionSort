Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


# Time Complexity: O(N^2)
# [22,27,16,2,18,6] için 18 sayısı en son sıralarda bulunduğu için Average Case ile Worst Case arasında olur.

## [22,27,16,2,18,6] aşamalar(küçükten büyüğe):

1: [2,27,16,22,18,6]
2: [2,6,16,22,18,27]
3: [2,6,16,22,18,27]
4: [2,6,16,18,22,27]
5: [2,6,16,18,22,27]
6: [2,6,16,18,22,27]

# İlk 4 aşama (küçükten büyüğe):
1: [2,3,5,8,7,9,4,15,6]
2: [2,3,5,8,7,9,4,15,6]
3: [2,3,4,8,7,9,5,15,6]
4: [2,3,4,5,7,9,8,15,6]
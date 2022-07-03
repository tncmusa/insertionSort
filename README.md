Proje 1 | Insertion Sort

www.patika.dev

## Time Complexity: O(N^2)
### [22,27,16,2,18,6] için 18 sayısı en son sıralarda bulunduğu için Average Case ile Worst Case arasında olur.

## [22,27,16,2,18,6] aşamalar(küçükten büyüğe):

1: [2,27,16,22,18,6] <br>
2: [2,6,16,22,18,27] <br>
3: [2,6,16,22,18,27] <br>
4: [2,6,16,18,22,27] <br>
5: [2,6,16,18,22,27] <br>
6: [2,6,16,18,22,27]

## İlk 4 aşama (küçükten büyüğe):
1: [2,3,5,8,7,9,4,15,6] <br>
2: [2,3,5,8,7,9,4,15,6] <br>
3: [2,3,4,8,7,9,5,15,6] <br>
4: [2,3,4,5,7,9,8,15,6]
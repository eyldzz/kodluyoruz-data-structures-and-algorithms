# P-1

## Selection Sort
### 1: [22,27,16,2,18,6] -> Insertion Sort <br> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- [22,27,16,2,18,6]
- [2,22,27,16,18,6]
- [2,6,22,27,16,18]
- [2,6,16,22,27,18]
- [2,6,16,18,22,27]

 ### Big-O gösterimini yazınız.
- `O(n²)`

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı case'lerden hangisinin kapsamına girer? Yazınız

`Average Case`

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
- [7,3,5,8,2,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]
- [2,3,4,5,6,7,8,15,9]
- [2,3,4,5,6,7,8,9,15] <br>


# P-2
## Merge Sort
### [16,21,11,8,12,22] -> Merge Sort <br>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

                             [16,21,11,8,12,22]
              [16,21,11]                            [8,12,22]
            [16,21]   [11]                        [8,12]    [22]
          [16] [21]    [11]                      [8] [12]    [22]
          [16,21]  [11]                         [8,12]    [22]
                       [11,16,21]           [8,12,22]
                            [8,11,12,16,21,22]
### Big-O gösterimini yazınız.
`O(nlogn)` <br>


# P-3
## Binary Search Tree
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. <br>Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
orta sayılabilecek değer olarak 6 yı ele alırsak
root = 6

                                  6
                                /   \
                               5     7
                             /         \
                           1             8
                         /   \            \
                       0       3           9
                             /   \
                            2     4



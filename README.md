
## Insertion sort Project
Q1:[22,27,16,2,18,6] -> Insertion sort

##### [2,27,16,22,18,6] n-1
##### [2,6,16,22,18,27] n-2
##### [2,6,16,18,22,27] 1

##### O(n^2)
##### Dizi sıralandıktan sonra 18 sayısı "Avarage case" kapsamına girer.

Q2: [7,3,5,8,2,9,4,15,6] dizisinin Insertion sort a göre ilk 4 adımını yazınız.

##### step1 [2,3,5,8,7,9,4,15,6]
##### step2 [2,3,4,8,7,9,5,15,6]
##### step3 [2,3,4,5,7,9,8,15,6]
##### step4 [2,3,4,5,6,9,8,15,7]

## Merge Sort Project

Q1:[16,21,11,8,12,22] -> Merge Sort

- [16,21,11] - - - [8,12,22]
- [16] - - [21,11] - - - [8,12] - - [22]
- [16,11,21] - - -[8,12,22]
- [11,16,21] - - -[8,12,22]
- [8,11,12,16,21,22]

O(nlogn)

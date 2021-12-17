# Proje 2 - Merge Sort
[16,21,11,8,12,22]

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız. 
```
    [16, 21, 11, 8, 12, 22]
        /\         /\
    [16,21,11] [8,12,22]
        /\         /\
    [16][21,11] [8,12][22]
          /\      /\   
    [16][21][11][8][12][22]
         /          \
    [16][11,21]   [8,12][22] 
        /             \
    [11,16,21]    [8,12,22]
        \             /
       [8,11,12,16,21,22]
```
Big-O gösterimi ;

n = 2^x

logn = x

O(nlogn)  
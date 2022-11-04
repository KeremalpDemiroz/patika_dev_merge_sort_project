# patika_dev_merge_sort_project
Patika.dev  Veri Yapıları ve Algoritmalar Merge Sort Projesi
 [Patika.dev](https://www.patika.dev/tr)


Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Aşamalar

Aşama 0 -> [16,21,11,8,12,22]

Aşama 1 ->     [16,21,11]                      [8,12,22]
Aşama 2 -> [16]         [21,11]           [8,12]       [22]  
Aşama 3 -> [16]      [21]     [11]      [8]    [12]    [22]
Aşama 4 -> [16]         [11,21]           [8,12]       [22]
Aşama 5 ->     [11,16,21]                      [8,12,22]
Aşama 6 ->                 [8,11,12,16,21,22]

Time Complexity
-> O(nlogn)

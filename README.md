# Merge-Sort
Merge Sort sistemi ile sıralama Odev 2


## [16,21,11,8,12,22] -> Merge Sort

                                                    [16,21,11,8,12,22] 

                                         [16,21,11]                     [8,12,22]
                                     [16]           [21,11]           [8]         [12,22]
                                     [16]         [21]   [11]         [8]        [12]  [22]
                                     [16]           [11,21]           [8]         [12,22]
                                         [11,16,21]                     [8,12,22]
                                                 
                                                     [8,11,12,16,21,22]


## Big-O gösterimi

n= 6  | logn = 6   -> O(nlogn) = O(6.6) = 36
# Merge-Sort-Projesi
Merge-Sort-Projesi Veri Yapıları Ödev2


Soru 1: [16,21,11,8,12,22] dizisini Merge Sort türüne göre aşamalarını yazınız.

                       [16,21,11,8,12,22]
                      /                \
                  [16,21,11]         [8,12,22]
                   /    \             /     \ 
               [16,21]   [11]      [8,12]    [22]
               /    \      \       /    \      \
             [16]   [21]   [11]  [8]    [12]   [22]
               \     /      /     \      /      /
               [16,21]    [11]     [8,12]     [22]
                  \        /          \       /  
                  [11,16,21]          [8,12,22]
                       \                 /
                       [8,11,12,16,21,22]
                       
                       
 Soru 2:Big-O gösterimini yazınız.
 
 O(n*(logn))

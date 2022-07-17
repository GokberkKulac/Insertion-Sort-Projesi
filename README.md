# Insertion-Sort-Projesi
Patika.dev İnsertion Sort Projesi çözümü.

Aşağıda görülen dizi kendi içinde dağınık bir şekilde bulunmaktadır. İnsertion Sort kullanarak sıralama yapacağız. 

## PROJE 1 
[22,27,16,2,18,6] -> Insertion Sort


### 1. INSERTION SORT AŞAMASI###
Veri örüntüsüne göre en küçük sayı bulunuyor ve en sola alınarak ilerleniyor.
    [22, 27, 16, 2, 18, 6] 
    [*2|, 27, 16, *22, 18, 6]
    [2, *6|, 16, 22, 18, *27] 
    [2, 6, 16|, 22, 18, 27] 
    [2, 6, 16, *18|, *22, 27] 
    [2, 6, 16, 18, 22|, 27]
    
### 2. BIG-O Notation###

     O(n^2)
    
### 3. TIME COMPLEXITY AŞAMASI###

    Average case: The number we are looking for is in the middle.
    Worst case: The number we are looking for is at the end.
    Best case: The number we are looking for is at the beginning.

### 4. 18 sayısının hangi case kısmında değerlendirirsek. ###

    Average case -> [2, 6, 16, 18, 22, 27] 

### Ekstara Örnek [7,3,5,8,2,9,4,15,6] ###
Write the first 4 steps of the array according to the Insertion Sort.

    Question: [2| , 3, 5, 8, 7, 9, 4, 15, 6]
    First step: [2, 3| , 5, 8, 7, 9, 4, 15, 6]
    Second step: [2, 3, 4| , 8, 7, 9, 5, 15, 6]
    Third step: [2, 3, 4, 5| , 7, 9, 8, 15, 6]
    Fourth step: [2, 3, 4, 5| , 6, 9, 8, 15, 7]

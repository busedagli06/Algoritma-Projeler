
# Insertion Sort Projesi
## 1. Dizinin sort türüne göre aşamaları [22,27,16,2,18,6] 
* [22, 27, 16, 2, 18, 6]
* [22, 27, 16, 2, 18, 6]
* [16, 22, 27, 2, 18, 6]
* [2, 16, 22, 27, 18, 6]
* [2, 16, 18, 22, 27, 6]
* [2, 6, 16, 18, 22, 27]
## 2. Big O Gösterimi
 n.(n+1)/2  
 =n^2  
 O(n^2) 
 ## 3. Time Complexity
## Average Case: 
* Aradığımız sayının ortada olmasıdır.  
O(n^2)
## Worst Case: 
* Aradığımız sayının sonda olmasıdır.(En son istenecek durum)  
O(n^2)
## Best Case: 
* Aradığımız sayının dizinin en başında olmasıdır.(En hızlı sonuç)  
O(n)
## 18 Sayısı hangi case kapsamına girer?
* Average Case
## 4. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı
Selection Sort algoritması, her adımda dizinin en küçük elemanını bulup başlangıçtaki elemanla değiştirir.
 * [2, 3, 5, 8, 7, 9, 4, 15, 6]
 * [2, 3, 5, 8, 7, 9, 4, 15, 6]
 * [2, 3, 4, 8, 7, 9, 5, 15, 6]
 * [2, 3, 4, 6, 7, 9, 5, 15, 8]  
#  Merge Sort(Proje 2)
 ## Dizinin sort türüne göre aşamaları[16,21,11,8,12,22]
 Merge Sort algoritması, bir diziyi sıralamak için aşağıdaki adımları izler:
 * Diziyi iki eşit parçaya böl.  
 Sol: [16, 21, 11]
 Sağ: [8, 12, 22]
 * Adım: Her iki parçayı da aynı algoritma ile sırala (rekürsif olarak).  
 Sol: [11, 16, 21]
 Sağ: [8, 12, 22]
 * İki sıralı parçayı birleştir.  
[8, 11, 12, 16, 21, 22]
## Big-O gösterimi
Big-O gösterimiyle O(n log n)'dir.





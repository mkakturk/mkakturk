[22, 27, 16, 2, 18, 6] -> Insertion Sort
Yukarıda gösterilen dizinin sort türüne göre aşamalarını yazın. Big-O gösterimini yazın.
 [2,27,16,22,18,6]1. adım 22 yerine gelebilecek en küçük sayı bulunması
 [2,6,16,22,18,27]2. adım ilk adım geçildikten sonra ki 27'den en küçük sayıyla yer değiştirilmesi
 [2,6,16,22,18,27] 3.aadım 16 için bakıldı ancak küçük değer bulunmadı.
 [2,6,16,18,22,27]4. adım 22 için bakıldı ve bulundu  ve sonraki adımlarda da doğru olduğu gözlemlendi.
 Big-O gösrerimi n+(n-1)+(n-2)... = (n^(n+1))/2 Big-0 gösterimi O(n^2)
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case' lerden hangisinin kapsamına girer yazınız.
Average Case: Aradığımız sayının ortada olması
Worst Case: Aradığımız sayının sonda olması
Best Case: Aradığımız sayının en başlarda olması
cevap=average case
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

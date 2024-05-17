# Proje-patika
Proje 1 için;
İlk olarak, verilen dizinin Insertion Sort ile sıralanması için adımları sıralayalım:

Verilen dizi: [22, 27, 16, 2, 18, 6]

[22, 27, 16, 2, 18, 6] -> 27'yi uygun konuma yerleştir (ilk elemandan önce).
[22, 27, 16, 2, 18, 6] -> 22'yi bırak ve bir sonraki elemana geç.
[22, 27, 16, 2, 18, 6] -> 16'yı uygun konuma yerleştir (ilk elemandan önce).
[16, 22, 27, 2, 18, 6] -> 2'yi uygun konuma yerleştir (ilk elemandan önce).
[2, 16, 22, 27, 18, 6] -> 18'i uygun konuma yerleştir (3. elemandan önce).
[2, 16, 18, 22, 27, 6] -> 6'yı uygun konuma yerleştir (ilk elemandan önce).
[2, 6, 16, 18, 22, 27] -> Tüm elemanlar sıralandı.
Big-O gösterimi için Insertion Sort'un average, worst, ve best case senaryoları için karmaşıklıkları aşağıdaki gibidir:

Average Case: O(n^2)
Worst Case: O(n^2)
Best Case: O(n)
Time Complexity:

Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

Verilen dizi küçükten büyüğe sıralandığında: [2, 6, 16, 18, 22, 27]

18 sayısı için:

Average case: Aradığımız sayının ortada olması -> 18, ortada bir elemandır.
Worst case: Aradığımız sayının sonda olması -> 18, dizinin sonunda yer alır.
Best case: Aradığımız sayının dizinin en başında olması -> 18, dizinin başında yer alır.
Yani, 18 sayısı için:

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
Şimdi, [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazalım:

Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

[2, 3, 5, 8, 7, 9, 4, 15, 6] -> En küçük elemanı bul ve ilk elemanla yer değiştir.
[2, 3, 4, 8, 7, 9, 5, 15, 6] -> En küçük ikinci elemanı bul ve ikinci elemanla yer değiştir.
[2, 3, 4, 5, 7, 9, 8, 15, 6] -> En küçük üçüncü elemanı bul ve üçüncü elemanla yer değiştir.
[2, 3, 4, 5, 6, 9, 8, 15, 7] -> En küçük dördüncü elemanı bul ve dördüncü elemanla yer değiştir.
Bu adımlar Selection Sort'un ilk 4 adımını temsil eder.


Proje 2
verilen dizi: [16, 21, 11, 8, 12, 22]

[16, 21, 11] ve [8, 12, 22] olarak ikiye böl.
[16, 21, 11] -> [11, 16, 21] olarak sırala.
[8, 12, 22] -> [8, 12, 22] olarak sırala.
Birleştir: [8, 11, 12, 16, 21, 22]
Big-O gösterimi:
Merge Sort'un karmaşıklığı her zaman O(n log n) olacaktır.

Proje 3
Binary Search Tree (BST), veri yapılarından biridir ve her bir düğümün sol alt ağacındaki tüm düğümlerin değerleri o düğümden daha küçük, sağ alt ağacındaki tüm düğümlerin değerleri ise o düğümden daha büyük olacak şekilde düzenlenmiştir.

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

BST oluşturulurken aşağıdaki adımlar takip edilir:

Root düğüm oluşturulur: 7
7'nin solundaki düğüme 5, sağında bulunan düğüme 8 değeri eklenir.
5'in soluna 1, sağuna 3 değerleri eklenir.
8'in sağına 9, 5'in sağındaki 3'ün soluna 6, solundaki 1'in sağına 2, 9'un soluna 4 ve 5'in soluna 0 değerleri eklenir.

[16, 21, 11] ve [8, 12, 22] olarak ikiye böl.
[16, 21, 11] -> [11, 16, 21] olarak sırala.
[8, 12, 22] -> [8, 12, 22] olarak sırala.
Birleştir: [8, 11, 12, 16, 21, 22]
Big-O gösterimi:
Merge Sort'un karmaşıklığı her zaman O(n log n) olacaktır.



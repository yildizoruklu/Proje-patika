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




# Insertion-Sort-Project
This document include first homework of Data Structures And Algorithms Course  from www.patika.dev


Proje 1
[22,27,16,2,18,6] -> Insertion Sort
----
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
---------
- [22,27,16,2,18,6]
- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]


Big-O gösterimini yazınız.
---------------------------
- [22,27,16,2,18,6]    (n)
- [2,27,16,22,18,6]    (n-1)
- [2,6,16,22,18,27]    (n-2)
- [2,6,16,18,22,27]    (n-3)

n*(n+1)/2 = (n+n^2)/2  burada enkare ifadesi baskın değerdir yanındaki en ifadesi enkare yanında önemsiz kalır.

Big-O gösterimi: O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
-------------------
-Average Case

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
-----------------
- [7,3,5,8,2,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]
- [2,3,4,5,6,7,8,15,9]
- [2,3,4,5,6,9,8,9,15]




# Veri Yapıları ve Algoritmalar

# INSERTION SORT PROJESİ

A.[22,27,16,2,18,6]

1. Yukarıda verilen dizinin sort türüne göre aşamalrı
1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,18,22,27]

2. Big-O gösterimi
worst case => n! =n*(n+1)/2 = (n^2+n)/2 = O(n^2)

3.Time Complexity
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması 
Best case: Aradığımız sayının dizinin en başında olması

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Average Case

B.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

# MERGE SORT

[16,21,11,8,12,22] 

A.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11] [8,12,22]
[16] [21,11] [8] [12,22]
[16] [21] [11] [8] [12] [22]
[16] [11,21] [8] [12,22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]

B.Big-O gösterimini yazınız.
O[nLogn]

www.patika.dev 


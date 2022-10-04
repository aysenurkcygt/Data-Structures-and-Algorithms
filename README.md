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

# BINARY SEARCH TREE PROJECT

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root=7
5 değeri roottan küçüktür bu nedenle sol tarafa yazılır.
1 değeri roottan küçüktür bu nedenle sola yazılır, 5'ten de küçük olduğu için 5'in soluna yazılır.
8 değeri roottan büyük olduğu için root'un sağ tarafına yazılır.
3 değeri roottan küçüktür, 5'ten de küçüktür ama 1'den büyüktür, bu nedenle 1'in sağ tarafına yazılır.
6 değeri roottan küçüktür, 5'ten de büyük olduğu için 5'in sağına yazılır.
0 değeri 7,5 ve 1'den küçüktür, bu nedenle 0'ın soluna yazılır.
9 değeri roottan ve 8'den büyüktür, bu nedenle 8'in sağına yazılır.
4 değeri roottan ve 5'den küçüktür, 1'den ve 3'ten büyük olduğu için de 3'ün sağına yazılır.
2 değeri 7'den de 5'den de küçüktür, 1'den büyüktür ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.

https://app.patika.dev/aysnrays


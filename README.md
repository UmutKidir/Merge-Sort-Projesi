# Proje

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


# Çözüm

* Problem 1

1. [16,21,11,8,12,22]
2. [16,21,11] - [8,12,22]
3. [16,21] - [11] - [8] - [12,22]
4. [16] - [21] - [11] - [8] - [12] - [22]
5. [16,21] - [11] - [8] - [12,22]
6. [11,16,21] - [8,12,22]
7. [8,11,12,16,21,22]

* Problem 2
O(nlogn)
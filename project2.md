# Merge Sort problem 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# Sorting Aşamaları
[16,21,11] --- [8,12,22]

[16,21] --- [11] --- [8,12] --- [22]

[16] --- [21] --- [11] --- [8] --- [12] --- [22]

[16,21] --- [11] --- [8,12] --- [22]

[11,16,21] --- [8,12,22]

[8,12,11,16,21,22]

# Big O notation

O(n*logn)
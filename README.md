# Binary Search Tree Projesi

[Patika.dev](https://www.patika.dev/)'in Veri Yapıları ve Algoritmalar dersinin proje ödevidir.

## [7,5,1,8,3,6,0,9,4,2] -> Binary-Search-Tree

### Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root 5'dir. root'un sağında 7,8,6,9 bulunur. Solunda 1,3,0,4,2 bulunur.

root 7'dir. root'un sağında 8,9 bulunur. Solunda 6 bulunur.

root 2'dir. root'un sağında 3,4 bulunur. Solunda 1,0 bulunur.

root 1'dir. root'un sağında birşey bulunmaz. Solunda 0 bulunur.

[1,3,0,4,2] [5] [7,8,6,9]

[1,3,0,4,2] [5] [6] [7] [8,9]

[1,0] [2] [3,4] [5] [6] [7] [8,9]

[0] [1] [2] [3,4] [5] [6] [7] [8,9]
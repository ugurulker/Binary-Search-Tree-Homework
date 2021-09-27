## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

                            5
                           / \
                          3   6
                         / \   \
                        2   4   7
                       /         \
                      1           8
                     /             \
                    0               9


**root 5'dir.**

**Root'un sağında 5'den büyükler bulunur. [6, 7, 8, 9]**

**Root'un solunda 5'den küçükler bulunur. [0, 1, 2, 3, 4]**

**Örnek olarak 5'den küçük olduğu için 3 rakamı sol tarafa yazıldı. Ama 4 rakamı 3'den büyük olduğu için 3'ün sağına yazıldı.**

**O(logn) Average case**

**O(n) Worst case**
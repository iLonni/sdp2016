Упражнение 7
===
TODO: Range


1. Търсене на елемент в двоично наредено дърво

2. Проверка дали съществува път от корена до листо в дърво
- вход: дърво от букви
- вход: низ
- изход: дали има път от корена до листо в дървото, представен от низа

3. Проверка за път равен на сума
- вход: дърво от цели числа
- вход: число, представяващо сумата на търсения път
- изход: път, сумата на чийто възли е равна на въведеното число

4*. Tree-List
- От двойчно наредено дърво, само с промяна на указателите да се направи двойно свързан списък

5. Изчислете израза, представен в двоично дърво по следния начин:
  израз: (5 + 2) * (10 -3) * 4 - 5
представяне:
              -
             /\
            *  5
          /  \
         *    4
       /   \
      +     -
     /\    /\
    5  2 10  3

6. При зададено дърво и
получаване на операция (+ или *) и частично покриващо дърво,
приложете опрецията върху оригиналното дърво използвайки
най-близкия елемент на покриващото дърво като втори операнд.
input: tree, operation, delta tree

tree:
         1
        / \
       /   \
      1     1
     / \   / \
    2   3 2   3
   /       \
  4         5

operation: *
operands tree:
     5
    /
   3

Result:
         5
        / \
       /   \
      3     5
     / \   / \
    6   9 10  15
   /       \
  12        25

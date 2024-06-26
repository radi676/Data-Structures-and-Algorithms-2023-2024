# Task: Склад за ядки (Medium) - [HackerRank](<https://www.hackerrank.com/contests/2-2023-2024/challenges/kosi>)


### Statement:

В склад са разположени последователно $N$ кашона с ядки. Първият кашон е на първа позиция, вторият на втора, а $N$-тия на $N$та. Кашонът на $N$-та позиция тежи $W[i]$ килограма. Дадени са $T$ на брой заявки за доставка на кашони. Една заявка изисква да се намерят позициите на точно два кашона, чиято сума от килограмите е равна на $X$. Важно: Винаги има точно едно уникално решение.


### Input format

Първият ред съдържа едно цяло число $T$ - броят на заявките

Всеки от следващите групи от по 3 реда е както следва:

Първият ред съдържа едно цяло число $X$ - килограми

Вторият ред съдържа едно цяло число $N$ - броят на кашоните в склада 

Третият ред съдържа $N$ на брой цели числа $W[i]$ - теглото на всеки един от кашоните в склада



### Output format

Печатаме $T$ на брой реда. Един ред съдържа 2 цели числа - позициите на кашоните, чийто сбор от килограмите е равен на $X$. Важно: Първо печатаме по-малката позиция от двете


### Samples


#### Sample Input 0
```
1
6
4
3 4 5 3
```

#### Sample Output 0
```
1 4
```

#### Explanation 0
Дадена е една заявка, в която търсим сумата от килограмите на 2 кашона да е равна на 6. Дадени са ни 4ри кашона в склада. Печатаме 1ви и 4ти, защото на тези позиции стоят кашоните, чийто сума е равна на 6. 

#### Sample Input 1
```
2
7
5
5 4 1 2 8
10
6
6 2 1 5 2 9
```

#### Sample Output 1
```
1 4
3 6
```

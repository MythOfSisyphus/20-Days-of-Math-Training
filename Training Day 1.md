#### Tuesday, 1 Oct
---
#### Problem 1
>You're given a $4\times 4$ grid with all entries are equal to $1$ except, one on the right of the bottom left corner which is $-1$. You may switch the signs of all numbers of a row, column, or a parallel to one of the diagonals. In particular, you may switch the signs of each corner square. Prove that at least one $-1$ will remain in the grid.

---
#### Problem 2
> There is a row of $1000$ integers. There is a second row below, which is constructed as follows. Under each number $a$ of the first row, there is a positive integer $f(a)$ such that $f(a)$ equals the number of occurrences of $a$ in the first row. In the same way, we get the $3rd$ row from the $2nd$ row, and so on. Prove that, finally, one of the rows is identical to the next row.

---
#### Problem 3
> Prove that among any ten consecutive integers at least one is relatively prime to each of the others.

*My attempt:* I haven't proved it yet. But yeah, now I understand *why it works?* more clearly. It works because for any ten consecutive integers we have $5, 3(4)$ and $2(1)$ integers multiple of $2, 3$ and $5$ respectively. And multiple of $2, 3$ and $5$ need not to be distinct. For example let's say we have integers from $2n+1,...,2n+10$ and $3|2n+1$ then $3$ also divides $2n+4, 2n+7$ and $2n+10$. Needless to say $2$ divides all even numbers and let's also assume that $5|2n+1$ then $5|2n+6$ as well then we're left with $2n+3, 2n+5$ and $2n+9$ which are relatively primes to each of ten integers. You can take any example with stated condition and see it holds.
I just found its solution and realized that I made a mistake of not counting multiples of $7$.

*Proper Solution:* Any interval of length $10$ has at least one integer not divisible by $2, 3, 5,$ or $7.$ In particular, notice that there will be:
- $5$ integers divisible by $2$.
- At most $2$ odd integers divisible by $3$.
- At most $1$ odd integer divisible by $5$.
- At most $1$ odd integer divisible by $7$.
Implying at least one integer is not divisible by any of those primes and hence satisfies the desired condition. (source: https://math.stackexchange.com/a/1140721/963173)

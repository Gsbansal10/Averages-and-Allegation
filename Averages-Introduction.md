# Averages- Introduction

The topic of averages is relatively simple in its concepts and the questions asked are not much difficult. Further, the questions from this topic are, generally, not asked directly but as an intermediate step to some other problem. Lets begin.

## What is an average?

In simple english, it is a analytical tool (just like percentages) that we use for our convinence in day-to-day life. Suppose that there are a 20 students in a class who have scored different marks out of $100$ in the exam, like this&mdash;
$$ 84,\quad 65,\quad 78,\quad 91,\quad 58,\quad \ldots $$

If someone asks you what are the marks obtained by the students of your class, what will you say?

Would you enumerate the marks obtained by each student for all 20 students? What if there were a 100 students or more? Won't that become too cumbersome and tedious?

See, it is clear that the person is asking you to get a general idea of the level of the students of your class. So it is more appropriate to tell him just one number which would give him a rough estimate of that. That number is called as _average_.

## Why do we need it?

In addition to the use-case shown above, we can understand another case where average is useful.

Suppose we have two classes of students&mdash; $A$ and $B$ having $100$ students in each class. We want to compare the level of students in each class. How can we do it?

One way is to add all the marks obtained by every student of a class and then see which is higher. For eg. if the total of class $A$ comes out at $8200$ and class $B$ come out at $7300$, then we can say that _in general_, the students of class $A$ have performed better than the students of class $B$.

I said _in general_ because it is not necessary that all the students of class $A$ might have performed better than all the students of class $B$. It may also have happened that some students of class $A$ may have gotten fewer marks than some students of class $B$, but overall, taken all students together, class $A$ is more perfomant than class $B$.

Now, there is one problem with this addition approach&mdash; humans are not naturally equipped to deal with large numbers so if we continue using $8200$ and $7300$ in our calculations, it would be a tedious and quite possibly, an error-prone task. So what do we do?

We can simply divide this total by the number of students to get a rough estimate of marks obtained by each student, i.e.&mdash;
$$ \text{average } = \frac{m_1 + m_2 + m_3 + m_4 + \ldots}{n} $$

where $m_1, m_2, m_3, \ldots$ are the marks obtained by each student and $n$ is the number of total students.

So in this case, the average of class $A$ is $8200/100 = 82$ and that of class $B$ is $7300/100 = 73$. Thus again, we can draw the same conclusion that class $A$ is better than $B$.

## Generalised idea of average

The general formula for average will always remain same&mdash;
$$ average = \frac{\text{Total quantity}}{\text{number of elements}}  $$

This formula may be needed to be framed differently in different context but general idea will always remain same as has been shown above. For eg&mdash;

-   To calculate average speed, we can write&mdash;
    $$ \text{Average Speed} = \frac{\text{Total~ distance}}{\text{Total~ time}} $$

-   If we are given that class A has $n_1$ students and has average marks $a_1$ and class B has $n_2$ students and has average marks $a_2$, then what will be the combined average of both the classes, then as per the general idea of averages &mdash;

$$
\begin{aligned}
average &= \frac{\text{Total marks}}{\text{Total number of students}} \cr
&= \frac{n_1 \times a_1 + n_2 \times a_2 }{n_1 + n_2} \cr
\end{aligned}
$$

This is called weighted average and is covered in the next article.

## Range of average

**Assertion&mdash;** The always of $n$ numbers always lies between the smallest and the largest of those $n$ numbers. To illustrate&mdash; If we have $4$ students who have scored $13, 16, 17, 19$ marks in a subject. So their average will lie between $13$ and $19$.

📜 **Proof**

To get the lower limit of the $average$, we can write all the terms from the point of view of the lowest term i.e. $13$. As per the formula of average&mdash;

$$
\begin{aligned}
\text{average} &= \frac{13+16+17+19}{4} \cr
\therefore\quad &= \frac{13 + (13+3) + (13+4) + (13+6)}{4} \cr
\therefore\quad &= \left(\frac{13+13+13+13}{4}\right) + \frac{3+4+6}{4} \cr
\therefore\quad &= 13 + \text{something}
\end{aligned}
$$

As $something$ is being added to $13$, so the average must be greater than $13$, which is the smallest value among the four.

Similarly, for the upper limit, we can write all the terms from the point of view of the highest term i.e. 19, like this&mdash;

$$
\begin{aligned}
\text{average} &= \frac{13+16+17+19}{4} \cr
\therefore\quad &= \frac{(19-6) + (19-3) + (19-2) + 19 }{4} \cr
\therefore\quad &= \left(\frac{19+19+19+19}{4}\right) - \left(\frac{6+3+2}{4}\right) \cr
\therefore\quad &= 19 - \text{something}
\end{aligned}
$$

As $something$ is being subtracted from $19$, the $average$ must be less than $19$.

Hence we have proved that the average lies between $13$ and $19$.

✍️ **Example**

### Suppose we have two students who have scored $20$ and $22$ marks out of a maximum of $25$ marks. What is their average?

**Solution**
Using the formula written above, we can calculate the average as &mdash;
$$ \text{average } = \frac{20 + 22}{2} = 21 \quad✅$$

## Visualisation of average

Let us reverse-engineer the above example.

If we know the average, we can rewrite those terms as&mdash;

-   $20 = \text{average} - 1 = 21-1$
-   $22 = \text{average} + 1 = 21+1$

> It means that the _surplus above the average and shortfall (deficiency) below the average are always equal_.

We can also understand this with the help of the formula&mdash;

$$
\text{average} = \frac{(21-1) + (21+1)}{2} \newline
\qquad \quad = \frac{(21 + 21) + (1-1)}{2}
$$

If you observe carefully, you will find that the surplus of $1$ above $21$ and the deficiency of $1$ below $21$ will cancel each other out so we get $21$ as the average.

### Visualisation from the middle

We can also understand it visually, like this &mdash;
$$ \underbrace{20\qquad\qquad\qquad\qquad22}_{\normalsize \longleftarrow2\longrightarrow} $$

We have already established in the previous section that the average always lies between the minimum and maximum values. So, the value of the average $(A)$ will lie between $20$ and $22$ but where?

As we have also illustrated that the surplus above the average and the shortfall below the average will be equal, the average $(A)$ will sit right in the middle of these two terms, like this&mdash;

$$ \overbrace{\underbrace{20 \qquad\qquad}_{\small \longleftarrow1\longrightarrow} A\underbrace{\qquad\qquad 22}_{\small \longleftarrow1\longrightarrow}}^{\normalsize \longleftarrow2\longrightarrow} $$
Take a good look at the above representation. In this picture &mdash;

-   $Shortfall = A-20$
-   $Surplus = 22-A$

And we can just put them equal&mdash;

$$
\begin{aligned}
Shortfall &= Surplus \cr
\therefore\quad A-20 &= 22 - A \cr
\therefore\quad A &= 21
\end{aligned}
$$

Again, we get $A=21$.

Note that this property is true for any number of terms. We will also show it for $3$ and more terms.

### Visualisation from the left end

We can also visualise the average from one end, lets say $20$.

See, if one number is $20$ and other one is also $20$, then the average would have been $20$ itself. We can visualise like this&mdash;

$$ 20 \quad\text{ ------ A ------ } B $$

But if one of the number is larger than $20$, then it will overshoot that horizontal line of average, like this&mdash;

$$ 20 \quad \text{--------- A ------\quad} \overset{\normalsize 2}{\overset{\LARGE\uparrow}{B}} $$

Here we have written $B$ as $20 + 2$ i.e. the surplus of $2$ over $20$ will now be used to raise the overall average of $A$ and $B$ by $2/2 = 1$.

Thus the average of entire system will be $20+1 = 21$.

We can also arrive at this result using the formula approach, like this&mdash;

$$
\begin{aligned}
\text{average} &= \frac{20 + 22}{2} \cr
&= \frac{20+(20+2)}{2} \cr
&= \frac{(20+20)}{2} + \frac{2}{2} \cr
&= 20 + 1 \Longrightarrow 21\cr
\end{aligned}
$$

### Assumed values of individual terms

Suppose we are given that the average of $n$ terms is $A$, then as far as their sum is concerned, their individual values do not matter. In other words &mdash;

$$
\begin{aligned}
A &= \frac{{Sum}}{n} \cr
\therefore\quad {Sum} &= n\times A \cr
\therefore\quad Sum &= \underbrace{A + A + A+ \cdots + A}_{n~terms}
\end{aligned}
$$

It means that even if we do not know the individual values of terms, we can assume them all to be equal to the average $A$, only for summation purposes.

## Conclusion of the above discussion

Based on the discussion above, we can make following conclusions &mdash;

> -   The average of any $n$ entities with values $a_1, a_2, a_3, \dots a_n$ is calculated as $(a_1 + a_2 + a_3 + \cdots + a_n)/n$.
> -   The average of $n$ entites always lies between the maximum and the minimum value of the entire set of entities.
> -   If we have been given $n$ items with average $A$, and a new item with value $x$ is added to the set, then &mdash;
>     -   to maintain the average $A$, the value of the new item $(x)$ must also be $A$.
>     -   if the value of the new item is less than $A$, the overall average will decrease.
>     -   if the value of the new item is more than $A$, the overall average will increase.

## ✍ Solved examples

### The average of three numbers is $32$. A fourth number is added and the average of the four numbers becomes $33$. Find the value of the fourth number.

**Solution**

🔴 **Using the formula**

Let the sum of first three numbers is $S_3$. Then as per the formula of average&mdash;
$$ 32 = \frac{S_3}{3} \Longrightarrow S_3 = 96 $$

Let the fourth number be $n$, then again applying the formula for all four numbers&mdash;

$$ 33 = \frac{(S_3 + n)}{4} \Longrightarrow n = 36 $$

This works but this can get pretty calculative. We can instead use the surplus method.

🌳 **Using the surplus method**

Think it like this&mdash; If the fourth number would have been $32$, the average would have remained same. The overall average has increased only because it is more than $32$.

So if we treat it as $32+x$, then we can say that to increase the average of $3+1 = 4$ numbers by $33-32 = 1$ unit, we need $4\times 1 = 4$ surplus. So the value of $x$ must be $4$. That means the value of the fourth number must be $32+4 = 36$.

Visually, We can visualise it like this&mdash;

$$
\begin{aligned}
33 \quad&------------- \cr
32 \quad&\text{---------------A, B, C---------\quad} \overset{\normalsize x}{\overset{\LARGE\uparrow}{D}} \cr
\end{aligned}
$$

In this figure, we have placed $A,~B$ and $C$ in the line of average $32$. As has been given that the average increases after the arrival of $D$, therefore $D$ must be of the form $32+x$.

Now, this $x$ has the responsibility of raising the average of $A, B, C~ and~ D$ by $1$. This is equivalent to 'donating' $1$ to each of the term. So $x$ must be $4$.

Thus $D$ must be equal to $32+4 = 36$.

You could also have visualised it like this&mdash;

If $D$ has been able to raise the average of three numbers to $33$, then $D$ itself must be greater than $33$ i.e. $D$ must be of the form $33+k$. The picture for that will look like this&mdash;

$$
\begin{aligned}
33 \quad&----------- \overset{\normalsize k}{\overset{\LARGE\uparrow}{D}}\cr
32 \quad&\text{------------ A, B, C -----------\quad} \cr
\end{aligned}
$$

Now this $k$ is used to raise the average of three numbers ($A, B, C$) by $1$, so its value must be $k = 3$. Therefore $D = 33+3 = 36$.

👉 Internalizing this process will give you an edge in all the questions of averages.

### A cricketer has a certain average for $9$ innings. In the tenth inning, he scores $100$ runs thereby increasing his average by $8$ runs. His new average is&mdash;

1. 20
2. 24
3. 28
4. 32
5. 36

🌳 **Solution**

Let his old average is $A$. Then visually&mdash;

$$
\begin{aligned}
A+8 \quad&----------- \overset{\normalsize k}{\overset{\LARGE\uparrow}{Xth}}\cr
A \quad&\text{------ I, II, III, IV ..... ------\quad} \cr
\end{aligned}
$$

As he has raised the average of his previous innings, that means, he has scored runs equivalent to his new average and he has some extra runs to _'donate'_ to previous innings.

In the $10th$ innings, he has raised the average of $9$ previous innings by $8$ runs therefore he has '_donated_' $8\times 9 = 72$ runs to previous innings to 'help' them rise to the new average.

Therefore his new average is $100-72 = 28$. **Ans** ✅

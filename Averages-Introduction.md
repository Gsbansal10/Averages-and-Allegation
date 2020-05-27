# Averages- Introduction

The topic of averages is relatively simple in its concepts and the questions asked are not much difficult. Further, the questions from this topic are, generally, not asked directly but as an intermediate step to some other problem. Let's begin.

## What is Average?

In simple English, it is a simplification tool (just like percentages) that we use for our convenience in day-to-day life. Suppose that 20 students in a class have scored different marks out of $100$ in the exam, like this&mdash;
$$ 84,\quad 65,\quad 78,\quad 91,\quad 58,\quad \ldots $$

If someone asks you what are the marks obtained by the students of your class, what will you say?

Would you enumerate the marks obtained by each student for all 20 students? isn't that tedious? What if there were 100 students or more? Won't that become too cumbersome? Well, you get the idea.

See, it is clear that the person is asking you to get a general idea of the level of the students in your class. So it is more appropriate to tell him just one number which would give him a rough estimate of that. That number is called as _average_.

## Why do we need average?

In addition to the use-case shown above, we can understand one another case where the average is useful.

Suppose we have two classes of students&mdash; $A$ and $B$ having $100$ students in each class. We want to compare the performance level of students in each class. How can we do it?

One way is to add the marks obtained by all students of a class and see which is higher. For eg. if the total of class $A$ comes out at $8200$ and class $B$ come out at $7300$, then we can say that _in general_, the students of class $A$ have performed better than the students of class $B$.

I said _in general_ because not all students of class $A$ may have performed better than all the students of class $B$. It may also have happened that some students of class $A$ may have gotten fewer marks than some students of class $B$, but overall, taken all students together, class $A$ is a better performer than class $B$.

Now, there is one problem with this addition approach&mdash; humans are not naturally equipped to deal with large numbers so if we continue using $8200$ and $7300$ in our calculations, it would be a tedious and quite possibly, an error-prone task. So what do we do?

We can simply divide this total by the number of students to get a rough estimate of marks obtained by each student, i.e.&mdash;
$$ \text{average } = \frac{m_1 + m_2 + m_3 + m_4 + \ldots}{n} $$

where $m_1, m_2, m_3, \ldots$ are the marks obtained by each student and $n$ is the total number of students.

So in this case, the average of class $A$ is $8200/100 = 82$ and that of class $B$ is $7300/100 = 73$. Thus again, we can draw the same conclusion that class $A$ is better than $B$.

## Generalized idea of average

The general formula for average will always remain same&mdash;
$$ average = \frac{\text{Total quantity}}{\text{number of elements}}  $$

This formula may be needed to be framed differently in a different context but the general idea will always remain the same as has been shown above. For eg&mdash;

-   To calculate average speed, we can write&mdash;
    $$ \text{Average Speed} = \frac{\text{Total~ distance}}{\text{Total~ time}} $$

-   If we are given that class A has $n_1$ students and has average marks $a_1$ and class B has $n_2$ students and has average marks $a_2$, then their combined average can be calculated as &mdash;

$$
\begin{aligned}
average &= \frac{\text{Total marks}}{\text{Total number of students}} \cr
&= \frac{n_1 \times a_1 + n_2 \times a_2 }{n_1 + n_2} \cr
\end{aligned}
$$

This is called the weighted average and is covered in the next article.

-   If a person offers successive discounts of $x\%$, $y\%$ and so on. Then the average discount in percents will be&mdash;
    $$ \text{average discount } = \frac{\text{Net discount in percent}}{\text{number of individual discounts}} $$

## Properties of Average

### Range of average

**Assertion&mdash;** The average of $n$ numbers always lies between the smallest and the largest of those numbers. To illustrate&mdash; If we have $4$ students who have scored $13, 16, 17, 19$ marks in a subject, their average will lie between $13$ and $19$.

📜 **Proof**

To get the lower limit of the $average$, we can write all the terms from the point of view of the lowest term $13$. As per the formula of average&mdash;

$$
\begin{aligned}
\text{average} &= \frac{13+16+17+19}{4} \cr
\therefore\quad &= \frac{13 + (13+3) + (13+4) + (13+6)}{4} \cr
\therefore\quad &= \left(\frac{13+13+13+13}{4}\right) + \frac{3+4+6}{4} \cr
\therefore\quad &= 13 + \text{something}
\end{aligned}
$$

As $something$ is being added to $13$, so the average must be greater than $13$.

Similarly, for the upper limit, we can write all the terms from the point of view of the highest term $19$, like this&mdash;

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

### Addition of a new item to a group

Suppose it is given that the average of $n$ numbers is $a$. A new item is included in this group. What should be the value of this new item so that the average of all items remains unchanged?

**Analysis**

Let the value of the new item is $x$. So, as per the formula of average&mdash;

$$
\begin{aligned}
average &= \frac{\text{Sum of all items}}{\text{number of items}} \cr
\therefore\quad a &= \frac{n\times a + x}{n+1} \cr
\therefore\quad an + a &= na + x \cr
\therefore\quad x &= a
\end{aligned}
$$

Thus the value of the new item must also be equal to the existing average $a$.

👉 You should always keep this result in mind. It is used in most of the questions for faster results.

💡 Based on this computation, we can also prove that &mdash;

-   If the value of the new item $x$ is less than the average $a$, then the overall average will decrease.
-   Similarly, if the value of the new item $x$ is more than the average $a$, then the overall average will increase.

## Visualization of average

✍️ **Example**

### Suppose we have two students who have scored $20$ and $22$ marks out of a maximum of $25$ marks. What is their average?

**Solution**
Using the formula written above, we can calculate the average as &mdash;
$$ \text{average } = \frac{20 + 22}{2} = 21 \quad✅$$

### Surplus and Deficit

Let us reverse-engineer the above example.

If we know the average, we can rewrite those terms as&mdash;

-   $20 = \text{average} - 1 = 21-1$
-   $22 = \text{average} + 1 = 21+1$

Observe that an equal amount - $1$ is being added and subtracted from the average $21$ in both the numbers.

> It means that the _surplus above the average and shortfall (deficiency) below the average are always equal_.

We can also understand this with the help of the formula&mdash;

$$
\text{average} = \frac{(21-1) + (21+1)}{2} \newline
\qquad \quad = \frac{(21 + 21) + (1-1)}{2}
$$

If you observe, you will find that the surplus of $1$ above $21$ and the deficiency of $1$ below $21$ will cancel each other out so we get $21$ as the average. So they have to be equal.

### Visualization from the middle

We can also understand it visually, like this &mdash;
$$ \underbrace{20\qquad\qquad\qquad\qquad22}_{\normalsize \longleftarrow2\longrightarrow} $$

We have already established in the previous section that the average always lies between the minimum and maximum values. So, the value of the average $(A)$ will lie between $20$ and $22$; but where?

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

👉 Note that this property is true for any number of terms. Below, we have shown it for $5$ numbers also.

### Visualization from the left end

We can also visualize the average from one end, lets say $20$.

See, if one number is $20$ and the other one is also $20$, then the average would have been $20$ itself, as [explained above](#addition-of-a-new-item-to-a-group). We can visualize like this&mdash;

$$ 20 \quad\text{ ------ A ------ } B $$

But if one of the numbers is larger than $20$, then it will overshoot that horizontal line of average, like this&mdash;

$$ 20 \quad \text{--------- A ------\quad} \overset{\normalsize 2}{\overset{\LARGE\uparrow}{B}} $$

Here we have implicitly written $B$ as $20 + 2$. Now, this surplus of $2$ will raise the overall average of $A$ and $B$ by $2/2 = 1$.

Thus the average of the entire system will be $20+1 = 21$.

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

Suppose we are given that the average of $n$ terms is $A$, then as far as their sum is concerned, their values do not matter. In other words &mdash;

$$
\begin{aligned}
A &= \frac{{Sum}}{n} \cr
\therefore\quad {Sum} &= n\times A \cr
\therefore\quad Sum &= \underbrace{A + A + A+ \cdots + A}_{n~terms}
\end{aligned}
$$

It means that even if we do not know the individual values of terms, we can assume them all to be equal to the average $A$, only for summation purposes.

### Surplus and deficit illustrated using five numbers

Let us once again see the surplus and deficit concept in action for five numbers.

Suppose we are given these five numbers &mdash; $31, \quad32, \quad 34,\quad 36,\quad 42$.

The average of these five numbers is $(31+32+34+36+42)/5 = 35$.

Surplus above $35$ is &mdash;

-   $36-35 = 1$
-   $42 - 35 = 7$

Total surplus = $1+7 = 8$ ✔️

And the deficit below $35$&mdash;

-   $35 - 34 = 1$
-   $35 - 32 = 3$
-   $35 - 31 = 4$

Total deficit = $1+3+4 = 8$ ✔️

Note that the surplus and the deficit are once again equal.

💡 **Please note** that this property is very very important in allegations equation and in solving questions in general. You will see it when we solve a few questions in the third article. So make sure that you understand it well and remember it.

## Conclusions from the above discussion

Based on the discussion above, we can make the following conclusions &mdash;

> -   The average of any $n$ entities with values $a_1, a_2, a_3, \dots a_n$ is calculated as $(a_1 + a_2 + a_3 + \cdots + a_n)/n$.
> -   The average of $n$ entities always lies between the maximum and the minimum value of the entire set of entities.
> -   If we are given $n$ items with average $A$, and a new item with value $x$ is added to the set, then &mdash;
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

This works but this can easily get pretty calculative if the values are not small enough. We can instead use the surplus method.

🌳 **Using the surplus method**

Think it like this&mdash; If the fourth number would have been $32$, the average would have remained $32$ itself. The overall average has increased only because this fourth number is more than $32$.

So if we treat it as $32+x$, then we can say that to increase the average of $3+1 = 4$ numbers by $33-32 = 1$ unit, we need $4\times 1 = 4$ surplus. So the value of $x$ must be $4$. That means the value of the fourth number must be $32+4 = 36$. **Ans** ✅

We can also visualize this thought process like this&mdash;

$$
\begin{aligned}
33 \quad&------------- \cr
32 \quad&\text{---------------A, B, C---------\quad} \overset{\normalsize x}{\overset{\LARGE\uparrow}{D}} \cr
\end{aligned}
$$

In this figure, we have placed $A,~B$ and $C$ in the line of average $32$. As has been given that the average increases after the arrival of $D$, therefore $D$ must be of the form $32+x$.

Now, this $x$ has the responsibility of raising the average of $A, B, C~ and~ D$ by $1$. This is equivalent to having a surplus which can '_donate_' $1$ to each of the four items. So $x$ must be $4$.

Thus $D$ must be equal to $32+4 = 36$.

Alternately, you could also have visualized it like this&mdash;

If $D$ has been able to raise the average of three numbers to $33$, then $D$ itself must be greater than $33$ i.e. $D$ must be of the form $33+k$. The picture for that will look like this&mdash;

$$
\begin{aligned}
33 \quad&----------- \overset{\normalsize k}{\overset{\LARGE\uparrow}{D}}\cr
32 \quad&\text{------------ A, B, C -----------\quad} \cr
\end{aligned}
$$

Now, this excess $k$ effectively raises the average of three numbers ($A, B, C$) by $1$, so its value must be $k = 3$. Therefore $D = 33+3 = 36$.

👉 Internalizing this process will give you an edge in all the questions of averages.

### A cricketer has a certain average for $9$ innings. In the tenth innings, he scores $100$ runs thereby increasing his average by $8$ runs. His new average is&mdash;

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
A \quad&\text{------ I, II, III, ..... IX ------\quad} \cr
\end{aligned}
$$

As he has raised the average of his previous innings, it means that after attaining this new average (A+8), he had some extra runs to _donate_ to his previous $9$ innings so that their average is increased by $8$ runs.

Therefore he has _donated_ $8\times 9 = 72$ runs to previous innings to _help_ them rise to the new average.

So this $Xth$ inning is left with $100-72 = 28$ runs which is the new average. **Ans** ✅

## The speed of the train in going from Nagpur to Allahabad is $100$ km/hr while when coming back from Allahabad to Nagpur, its speed is $150$ km/hr. Find the average speed during the whole journey.

1. 125
2. 75
3. 135
4. 140

**Solution**

Let the distance between the two places be $d$. Then&mdash;

-   Total distance covered in the entire journey $= d + d \Longrightarrow 2d$
-   Total time taken in the entire journey $= d/100 + d/150 \Longrightarrow d/60$

As per the formula, the average will be &mdash;
$$ \text{average speed} = \frac{2d}{(d/60)} \Longrightarrow 120 ~km/h \quad✅$$

👉 **Note** if the speeds are given as $S_1$ and $S_2$, then the average speed can be calculated as &mdash;
$$ \text{average speed} = \frac{2d}{(d/S_1 + d/S_2)} \Longrightarrow \frac{2\times S_1\times S_2}{(S_1 + S_2)} $$

💡 You should remember this formula to get faster results.

## If two successive discounts of $10\%$ and $20\%$ are offered on a product, then what is the average discount?

**Solution**

Note that the discounts are offered on the Marked Price of the product.

Let the marked price of the product is Rs. $100$. Then&mdash;

-   Price after first discount of $10\%\Longrightarrow 100\times (100-10)/100 = 90$
-   Price after second discount of $20\%\Longrightarrow 90\times (100-20)/100 = 72$

Thus the net discount comes out as $\Longrightarrow (100-72)\times 100/100 = 28\%$.

Thus the average discount is $28/2 = 14\%$. **Ans** ✅

## Things to remember

**If a group of numbers has an average $A$, and we add $k$ to all the individual numbers, the average of the entire group becomes $A+k$.**

📜 **Proof&mdash;**

Let the individual numbers be $a_1, a_2, a_3, \ldots, a_n$. Thus &mdash;

$$
\begin{aligned}
\frac{a_1 + a_2 + a_3 + \ldots + a_n}{n} &= A \cr
\therefore\quad a_1 + a_2 + a_3 + \ldots + a_n &= A\times n
\end{aligned}
$$

Again, Let the new average is $A'$ after adding $k$ to each item&mdash;

$$
\begin{aligned}
\frac{(a_1+k) + (a_2+k) + (a_3+k) + \ldots + (a_n+k)}{n} &= A' \cr
\therefore\quad \frac{a_1 + a_2 + a_3 + \ldots + a_n}{n} + \frac{\overbrace{k + k+k+\ldots+k}^{\text{n times}}}{n} &= A' \cr
\therefore\quad A + \frac{n\times k}{n} &= A' \cr
\therefore\quad A' &= A + k
\end{aligned}
$$

Hence the new average $A'$ is $k$ more than the previous average. **Proved** ✅

### Corollary&mdash;

-   To increase the average of $n$ items by $1$, we need to add $1$ to each item of the set. Alternately, to decrease the average of $n$ items by $1$, we need to subtract $1$ from each item.
-   If the average age of a group of people is $n$, then $x$ years later, their average age will become $n+x$ since everybody is $x$ years older now.

# Weighted Average, Allegations and Mixture

## Definition and formula

If we are given $k$ groups with number of elements as $n_1, n_2, n_3, \ldots, n_k$ and their averages as $a_1, a_2, a_3, \ldots a_k$ then their accumulated average is &mdash;
$$ average = \frac{n_1\times a_1 + n_2\times a_2 + n_3\times a_3 + \ldots +n_k\times a_k}{n_1 + n_2 + n_3 + \ldots + n_k} $$

If we are given three or more groups then we have no option but to apply the formula but if we are given just two groups, we can apply the concept of surplus and deficit. This process has been explained below&mdash;

## Visualisation of weighted average for two groups

Let us assume that we are given two groups having one element each and their averages are $20$ and $23$. Let us visualise them like this &mdash;

$$
\text{\small Lower average}\underset{\small1}{\overset{\normalsize20}{\LARGE|}}
	\underbrace{\text{------------ }}_{\small x}
		\text{A}
	\underbrace{\text{ ------------}}_{\small y}
\underset{\small1}{\overset{\normalsize23}{\LARGE|}}\text{\small Higher average}
$$

Let $A$ be the average which lies between $20$ and $23$. Apply $Suplus = Deficit$&mdash;
$$ A - 20 = 23 - A \Longrightarrow A = 21.5 ~~✅$$

In other words, we can say that their respective distances from the average $A$ will be equal.

Thus $x=1.5$ and $y=1.5$, $A = 20+x\Longrightarrow 21.5$. ✅

It was simple enough when there is only one element in each group. But what if we are given that there is one element in the first group and two elements in the second group. How could we find the combined average then?

Well, for starters, we could represent them like this &mdash;

$$
\underset{\small1}{\overset{\normalsize20}{\LARGE|}}
	\underbrace{\text{------------ }}_{\small x}
		\text{A}
	\underbrace{\text{ ------------}}_{\small y}
\underset{\small2}{\overset{\normalsize23}{\LARGE|}}
$$

As you might observe, the average $A$ will gravitate towards $23$ because there are two of them. But the basic condition of the average&mdash; _that the surplus and the deficit are always equal_&mdash; will still hold.

The surplus above is now $y\times 2 = 2y$. And the deficit is $x\times 1 = x$. Thus&mdash;

$$ x = 2y $$

and $x + y = 23-20 = 3$. Thus $x = 2~ and~ y = 1$.

The average will be $20 + x \Longrightarrow 22$. **Ans** ✅

You can verify it using the formula for averages&mdash;
$$ average = \frac{20 + 23\times 2}{3} = 22 $$

👉 Solving the questions using the surplus and deficit approach can help you get answer faster.

💡 **Note** that if you find the surplus and deficit approach cumbersome or not applicable in any question, then you can always revert to the standard formula of averages. That will work in all situations.

### Generalization of this approach

Suppose we are given $2$ groups $P$ and $Q$. The number of elements in $P$ is $n_1$ and its average is $a_1$. The number of elements in $Q$ is $n_2$ and its average is $n_2$. This situation can be represented as follows &mdash;

$$
\text{\small Lower average}\underset{\small n_1}{\overset{\normalsize a_1}{\LARGE|}}
	\underbrace{\text{------------ }}_{\small x}
		\text{A}
	\underbrace{\text{------------ }}_{\small y}
\underset{\small n_2}{\overset{\normalsize a_2}{\LARGE|}}\text{\small Higher average}
$$

The deficit will be equal to the surplus. Therefore&mdash;

$$
n_1\times (A-a_1) = n_2\times (a_2 - A) \newline
\frac{n_1}{n_2} = \frac{y}{x}
$$

This equation is called the _Allegation Equation_. In plain English, it means that the number of elements in the groups are in the inverse ratio of respective distances from the average.

Note that if you rearranged the terms of this equation, we would have gotten &mdash;

$$
\begin{aligned}
(n_1\times A) - (n_1\times a_1) &= (n_2 \times a_2) - (n_2\times A) \cr
\therefore\quad (n_1 + n_2)\times A &= n_1\times a_1 + n_2\times a_2 \cr
\therefore\quad A &= \frac{n_1\times a_1 + n_2\times a_2}{n_1 + n_2}
\end{aligned}
$$

which is exactly what we would have obtained had we applied the formula directly.

💡 **Pro Tip&mdash;** Use the allegation equation when any of the $a_1, a_2, n_1, n_2$ is to be computed. Use the formula if the value of the accumulated average $A$ is to be determined.

✍️ **Solved examples**

### A 5 kg of salt costing Rs. 5/kg and 3 kg of salt costing Rs. 4/kg are mixed. Find the average cost of the mixture per kilogram.

**Solution**
It is easier with the direct application of the formula&mdash;
$$ Average = \frac{5\times 5 + 3\times 4 }{5+3} = 4.675 \quad✅ $$

### Two types of oils having the rates of Rs. 4/kg and Rs. 5/kg respectively are mixed in order to produce a mixture having the rate of Rs. 4.60/kg. What should be the amount of the second type of oil if the amount of the first type of oil in the mixture is 40 kg?

**Solution**

If you do it with the traditional formula of weighted average, it would take significant time. You can instead use the allegation equation, &mdash;
$$ \frac{n_1}{n_2} = \frac{y}{x} = \frac{a_2 - A}{A - a_1} $$

Here $n_1$ is $40$, $A$ is $4.60$, $a_2$ is $5$, $a_1$ is $4$. We can just put the values in the equation and get $n_2$, like this &mdash;
$$ n_2 = \frac{n_1\times (4.6-4)}{5-4.6} \Longrightarrow 60 \quad✅$$

Visually, you could have just made a diagram and surmise the result easily like this &mdash;

$$
\underset{\small 40}{\overset{\normalsize 4}{\LARGE|}}
	\overbrace{\text{------------ }}^{\small .6}
		\text{4.6}
	\overbrace{\text{------------ }}^{\small .4}
\underset{\small n_2}{\overset{\normalsize 5}{\LARGE|}}
$$

$$
\begin{aligned}
\frac{40}{n_2} &= \frac{0.4}{0.6} \cr
\therefore\quad n_2 &= 60 \quad ✅
\end{aligned}
$$

## Mixture

The questions related to mixing of materials (generally liquids like milk and water, oil and water etc) fall under this category.

The point to remember in these questions is that once these individual components are mixed, the resultant mixture is assumed to be homogeneous i.e. the ratio of liquids will be same in every drop of it.

✍️ **Examples&mdash;**

### A container has $50$ litres mixture of oil and water in ratio of $1:9$. If $5$ litres of this mixture is taken out and thrown away, what would be amount of each liquid left in the container?

**Solution**

The original quantity of oil and water would be $5$ and $45$ respectively.

And, as the mixture is homogeneous, the $5$ litres of liquid that was thrown away, also had liquids in ratio of $1:9$ i.e. $0.5$ litres of oil and $4.5$ litres of water.

Therefore we are left with $5 - 0.5 = 4.5$ litres of oil and $45 - 4.5 = 40.5$ litres of water. **Ans** ✅

💡 Observe that the ratio of liquids in the remaining mixture is also $4.5: 40.5 \Longrightarrow 1:9$. And it has to be because it is a homogeneous mixture.

### A mixture of $70$ litres of alcohol and water contains $10\%$ of water. How much water must be added to the above mixture to make the water $12.5\%$ of the resulting mixture?

**Solution**

In this question, you can observe that the absolute amount of alcohol is not changing at all. It remains same through out the process. So we will solve the question from the point of view of this constant amount.

Initially, the alcohol is $90\%$ of the mixture i.e. $70\times 90/100 = 63$ litres.
After mixing of water, the water becomes $12.5\%$, that means the milk will become $100-12.5 = 87.5\%$ of the mixture.

But as we said that the absolute amount of the milk is constant at $63$, therefore this $63$ litres is now $87.5\%$ of the final volume of the mixture. If we assume this volume as $v$, then&mdash;
$$ v\times 87.5/100 = 63 \Longrightarrow v = 72 $$

Final volume of mixture is $72$ litres whereas the initial volume was $70$ litres.

Therefore $72-70 = 2$ litres of water must have been added to the mixture. **Ans** ✅

In the next article, we will solve tons of interesting problems, so buckle up!!

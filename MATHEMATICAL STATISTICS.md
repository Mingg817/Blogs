# MATHEMATICAL STATISTICS

## Random variables 

A **random variable** is a **function** that assigns a **numerical value** to each possible **outcome** of a random experiment, capturing important aspects of those outcomes in a simplified form. 

**Discrete vs. Continuous**

​	•	**Discrete** 离散的: If the random variable has a finite or countably infinite set of values (e.g., count of allergic reactions), it’s discrete.

​	•	**Continuous**: If it can take any real number in a range, it’s continuous.

**Example:**

-   In a dice game, let X be the outcome of a single roll. Here, X can be any integer from 1 to 6.
-   In a study measuring people’s heights, let Y represent the height of a randomly selected person. Here, Y is continuous, as it can take on any value within a range (e.g., 150 cm to 200 cm).

>   A random variable is usually denoted by a **capital letter** (e.g., X , Y ), and its **specific values** are represented by **lowercase letters** (e.g., X = 3 means the random variable X takes the value 3).

$X(s) = t$ means that the **random variable** X assigns the value $t$ to the **sample outcome** $s$ .

## Binomial distribution

**Probability Formula for the Binomial Distribution**

The probability of having exactly $k$ successes in $n$ trials is given by:
$$
P(X = k) = \binom{n}{k} p^k (1 - p)^{n - k}
$$
where:

-    $P(X = k)$ is the probability of getting exactly k successes.
-   $\binom{n}{k} = \frac{n!}{k!(n-k)!}$ is the **binomial coefficient** (number of ways to choose k successes from n trials).
-   $p$ is the probability of success on each trial.
-   $1 - p$ is the probability of failure on each trial.
-   $n - k$ is the number of failures.
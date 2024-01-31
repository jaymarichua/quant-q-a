<h6>Infinite expected values</h6>

<h6>St. Petersburg paradox</h6>

Problem Example:

Suppose you are invited to play a game where you flip a fair coin repeatedly until you obtain heads for the first time. If the first heads appear on the $n^{th}$ flip, you will paid $\$2^n$. What is the fair value of this game?

The number of flips needed to see the first head follows a geometric distribution with probability $p = 1/2$. We want to find the expected value of $2^N$, where $N$ is the number of flips until the first heads, which is our expected payout. Mathematically, this is represented as:

$$E[2^N] = sum_{n=1}^{\infty} 2^n \cdot P[N=n] = \sum_{n=1}^{\infty} 2^n \cdot \frac{1}{2^n} = \sum_{n=1}^{\infty} 1 = \infty$$

_Ref._ _Expected Value. Wikipedia. Retrieved 19:18, January 31, 2024 from https://en.wikipedia.org/wiki/Expected_value_

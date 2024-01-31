<h4> Expected Value </h4>

$$E[X] = \sum_{i=1}^{\infty} x_i p_i$$

The expected value of a random variable $X$ is often denoted by $E(X), E[X], or EX$, with a stylized $E$.

<h5>Infinite expected values</h5>

<h5>St. Petersburg paradox</h5>

<h6>Problem Example:</h6>

Suppose you are invited to play a game where you flip a fair coin repeatedly until you obtain heads for the first time. If the first heads appear on the $n^{th}$ flip, you will paid $\$2^n$. What is the fair value of this game?

_Solution:_

The number of flips needed to see the first head follows a geometric distribution with probability $p = 1/2$. We want to find the expected value of $2^N$, where $N$ is the number of flips until the first heads, which is our expected payout. Mathematically, this is represented as:

$$E[2^N] = sum_{n=1}^{\infty} 2^n \cdot P[N=n] = \sum_{n=1}^{\infty} 2^n \cdot \frac{1}{2^n} = \sum_{n=1}^{\infty} 1 = \infty$$

Here is another example, _Example 4.3.14 (St. Petersburg paradox) from Introduction to Probability by Blitzstein and Hwang, Harvard and Stanford._

Suppose a wealthy stranger offers to play the following game with you. You will flip a fair coin until it lands Heads for the first time, and you will receive $2 if the game lasts for 1 round, $4 if the game lasts for 2 rounds, $8 if the game lasts for 3 rounds, and and in general, $2^n if the game lasts for $n$ rounds. What is the fair value of this game (the expected payoff)? How much would you be willing to pay to play this game once?

_Solution:_

Let $X$ be your winnings from playing the game. By definition, $X = 2^N$ where $N$ is the number of rounds that the game lasts. Then $X$ is 2 with probability 1/2, 4 with probability 1/4, 8 with probability 1/8, and so on, so

$$E[X] = \frac{1}{2} \cdot 2 + \frac{1}{4} \cdot 4 + \frac{1}{8} \cdot 8 + ... = \infty$$

The expected winnings are infinite! On the other hand, the number of rounds $N$ that the game lasts is the number of tosses until the first Heads, so $N ~ FS(1/2)$ and $E(N) = 2$. Thus $E(2^N) = \infty$ while $2^{E(N) = 4}$. Infinity certainly does not equal 4, illustrating the danger of confusing $E(g(X))$ with $g(E(X))$ when $g$ is not linear.

This problem is often considered a paradox because although the game's expected payoff is infinite, most people would not be willing to pay very much to play the game (even if the can afford to lose the money). One explanation is to note that _the amount of money in the real world is finite._ Suppose that if the game lasts longer than 40 rounds, the wealthy stranger flees the country and you get nothing. Since 2^40 is around 1.1 x 10^12, this still gives you the potential to earn over a trillion dollars, and anyway it's incredibly unlikely that the game will last longer than 40 rounds. But in this setting, your expected value is

$$E(X) = \sum_{n=1}^{40} \frac{1}{2^n} \cdot 2^n + \sum_{n=41}^{\infty} \frac{1}{2^n} \cdot 0 = 40.$$

... The $\infty$ in the St. Petersburg paradox is driven by an infinite "tail" of exteremely rare events where you get extremely large payoffs. Cutting off this tail at some point, which makes sense in the real world, dramatically reduces teh expected value of the game.

<h5>Martingale</h5>

Martingale is an instantiation of the St. Petersburg paradox.

_Ref._ _Expected Value. Wikipedia. Retrieved 19:18, January 31, 2024 from https://en.wikipedia.org/wiki/Expected_value_

_Ref._ _Martingale. Wikipedia. Retrieved 20:46, January 31, 2024 from https://en.wikipedia.org/wiki/Martingale_(betting_system)_

Blitzstein, J., & Hwang, J. (2009). Introduction to Probability. Harvard University and Stanford University.

<h6>Geometric series</h6>

$$\sum_{k=0}^{\infty} a r^k$$

The geometric series is often used in word problems relating to probability.

Example:

Abby and Ben are engrossed in a coin flipping game. Abby's coin isn't like most coins. It shows heads with a probability $p$ on every flip. Ben, on the other hand, possesses a regular coin that's fair. The game goes like this: Abby flips her coin first, followed by Ben, and they take turns in this manner. The game ends when one of them flips a heads. The first one to achieve this feat is declared the winner.

Here's the intriguing part: it's known that both Abby and Ben have equal chances of winning this game. Based on this, can you determine the value of $p$?

To find the probability $p$ of Abby's coin showing heads, given that both Abby and Ben have equal chances of winning the game, we need to analyze the possible outcomes of their turns.

Abby can win in multiple ways:
1. She flips heads on her first turn. 
2. Both she and Ben get tails on their first flips, and she flips heads on her second turn.
3. They both continue getting tails until Abby's $k$-th turn (for odd $k$), where she flips heads.

Since Abby and Ben flip their coins alternatively, starting with Abby, Abby's potential winning flips are the 1st, 3rd, 5th, etc. The probability of Abby winning on her $k$-th turn, where $k$ is odd, is $p x ((1-p) x 0.5)^{(k-1)/2}$. This expression considers that both have been flipping tails until Abby's $k$-th turn.


_Ref._ _Geometric Series. Wikipedia. Retrieved 02:17, January 31, 2024, from https://en.wikipedia.org/wiki/Geometric_series_
_Ref._ _Coin Flipping Game. Tradermath. Retrieved 02:25, January 31, 2024, from https://www.tradermath.org/brainteasers/coin-flipping-game_

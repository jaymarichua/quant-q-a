<h5>Combinatorics</h5>

The topic of combinatorics in word problems involves figuring ways of counting large number of outcomes, i.e. possibilities in relating to probability and statistics.

<h6>Rule of Product</h6>

If there are $m$ ways to arrange something, and then $n$ ways to arrange something else after that, then the number of ways to arrange both of those things is $m×n$.

<h6>Rule of Sum</h6>

If there are $m$ ways to arrange something, and there are $n$ ways to arrange something else, and these arrangements cannot both happen, then the number of ways to arrange both of those things is $m×n$.

<h6>Principle of Inclusion and Exclusion</h6>

The utility of both rules are extended by other principles to solve harder problems, such as using subtraction in the case of double counting, which can be generalized with the principle of inclusion and exclusion.To form an intuition for this principle, think of Venn diagrams where $P \cup S = P + S - P \cap S$. 

<h6>Permutation</h6>

Given a set of $n$ distinct objects, let the set of permutations of those objects be $P$. Then, $|P|=n!$. If there are $n$ ways to choose the 1st object, then the number of possible sequences are $n×(n-1)×(n-2)×...×1 = n!$.

With regards to subsets, given a set of $n$ objects, let the set of permutations of $k$ of those objects be $S$. Then, $|S|=n!/(n-k)!$.

<h6>Combination<h6>

Given a set of $n$ distinct objects, let $C$ be the set of combinations of $k$ of those objects. Then, $|C|=n!/(k!(n-k)!)$.

With regards to subsets, the number of permutations of $k$ objects from a set of $n$ objects is $n!/(n-k)!$. For each subset of $k$ objects from the set of $n$ objects, there are $k!$ permuations of that subset. Therefore, the number of combinations of $k$ objects from a set of $n$ objects is $n!/(k!(n-k)!)$.

<h6>Binomial Theorem</h6>

Combinatorics is involved with counting the coefficients expanded polynomial of a sum of two terms. The binomial theorem states that for any positive integer $n$, $$(x+y)^n=\binom{n}{0}x^n+\binom{n}{1}x^{n-1}y+...+\binom{n}{n-1}xy^{n-1}+\binom{n}{n}y^n=\sum_{k=0}^n\binom{n}{k}x^{n-k}y^k$$

Establishing a bijection between the products of a binomial rasied to $n$ and the combinations of $n$ objects, then each product which results in $a^{n-k}b^{k}$ corresponds to a combination of $k$ objects out of $n$ objects. Thus, each $a^{n-k}b^k$ term in the polynomial is derived from the sum of $\binom n k$ products.

<h5>Commonly Appearing Combinatorics Word Problems</h5>

Worth mentioning is that there are commonly appearing combinatorics word problems relating to other topics in mathematics, such as color parity, graph traversal, recursion, distribution of objects into bins, partition of an integer, pigeonhole principle, and grid walking.

<h6>Number of ways to put objects into bins</h6>

Forming an intuition with combinatorics word problems comes with experience, but another way to approach the problems is by thinking of the combination as a selection of two sets of items as we are counting those that go into the chosen bin, $k$, and counting those that go into the unchosen bin, $n-k$. This can be generalized to any number of bins with the constraint that every item must go to exactly one bin. Note that the number of ways to put objects into bins is given by the multinomial coefficient. $$\binom{n}{k_1,k_2,...,k_m}=\frac{n!}{k_1!k_2!...k_m!}$$, where every equivalence class consists of $k_1!k_2!...k_m$ distinct numberings, and the number of equivalence classes is $\frac{n!}{k_1!k_2!...k_m!}$.

<h5>References</h5>

_Ref._ _Combinatorics. Brilliant.org. Retrieved 17:22, January 23, 2024, from https://brilliant.org/wiki/combinatorics/_

_Ref._ _Advanced Examples, Combinations. Brilliant.org. Retrieved 04:01, January 24, 2024, from https://brilliant.org/wiki/combinations/_

_Ref._ _Principle of Inclusion and Exclusion (PIE). Brilliant.org. Retrieved 22:55, January 23, 2024, from https://brilliant.org/wiki/principle-of-inclusion-and-exclusion-pie/_

_Ref._ _Combination. Wikipedia. Retrieved 10:19, January 24, 2024, from https://en.wikipedia.org/wiki/Combination_

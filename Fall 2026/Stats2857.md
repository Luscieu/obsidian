For the union of two probabilities that are not mutually exclusive:
we must subtract where it intersects, to remove the overlap that is counted twice; P($A \cup B$) = P(A) + P(B) - P($A \cap B$)

for 3 probabilities, you need to subtract the union between each as well adding the union between all three back

Permutation P: ${}_nP_{k} = \frac{n!}{(n-k)!}$
- permutation is ordered, so it is used in cases without replacement as well as order

Combination(read as n choose k) ${}_nC_{k}=\binom{n}{k} = \frac{{}_nP_{k}}{k!}= \frac{n!}{k!(n-k)!}$
- Combinations are unordered sets of distinct objects
	- where n is number of objects and k is number chosen for the subset
	- dividing by k! just removes the ordered combination possibilities

Conditional Probability:
$P(A\mid B)= \frac{P(A \cap B)}{P(B)}$ 
- Read as the probability of A given B
	- Given that B has already occurred, what is the probability of A

Naive Algo - Defn to algo slow

Algo by way of standard tools - standard tech

Optimized Algo - Improve existing algo

f(n) = O(g(n)) - > if n >= N , f(n) <= c * g(n) for constants c and N

Common growth rules
7n^3 = O(n^3)
n^2/3 = O(n ^ 2)
n = O(n ^2) , Sqrt(n) = O(n)
n^5 = O(Sqrt(n) pow n )
n pow 100 = O(1.1n)
(log n ) pow 3 = O(Sqrt(n))
n log n = O(n pow 2)
n pow 2 + n = O(n pow 2)
2 pow n + n pow 9 = O(2 pow n)

f(n) = Big Omega(g(n)) -> f grows no slower than g
f(n) = Big theta(g(n)) -> f grows same rate as g
f(n) = (little o) o(g(n)) -> f grows slower than g

The main rules for working with logarithms are the following:

loga(n pow k)=k loga n
loga(nm)=loga n+loga m
n pow loga b=b pow loga n
loga n⋅logb a=logb n

greedy strategy (for arranging a set of numbers in desc order)
1: Find the largest number in the list
2: Append it to the list
3: Remove it from list
4: Repeat

Genralizing
Make some greedy choice
Reducde to a smaller sub problem
iterate

Safe Move: Greedy choice is a safe move if it is consistent with some optimal choice

Genral Statergy:
Make a greedy choice 
prove that it is a safe move
reduce it to a sub problem
solve the subproblem in the same way

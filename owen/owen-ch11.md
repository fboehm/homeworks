Chapter 11 Exercises from [Monte Carlo theory, methods, and
examples](https://statweb.stanford.edu/~owen/mc/)
================
Frederick J. Boehm
7/13/2020

> 11.1. Consider the Montr´eal metro walk of \[\S\] 11.2, for a walker
> starting at X0 = Snowdon. a) Plot PSnowdon(Xn = Berri-UQAM) as a
> function of n for n = 1, . . . , 1000. Make a second plot just for n =
> 1, . . . , 10.

We first recall the notation: \[P_{start}(X_n = end)\] denotes the
probability, when starting at ‘start’, that \(X_n\) takes the value
“end”.

So, we need to start at Snowdon and determine the probability that
\(X_n\) is Berri-UQAM.

He gives us the transition matrix for a single time unit in Expression
11.10 on page 10 of the pdf.

\[P = \left(\begin{array} 
0 & 1/2 & 0 & 1/2 & 0 \\
1/2 & 0 & 1/2 & 0 & 0
\end{array}\right)\]

> 2)  Suppose that the walker changes behavior and does not linger at
>     Longueuil. Instead, every visit to Longueuil is immediately
>     followed by a visit to BerriUQAM. Write the transition matrix Pe
>     for this version of the walk. With this change in the Markov
>     chain, repeat part a.
> 3)  Now suppose that the walker always has probability 1/2 of
>     lingering. Specifically, let Pe be the transition matrix from part
>     b, let I5 be the 5 by 5 identity matrix, and define P¯ = (Pe +
>     I)/2. Repeat part a using the transition matrix P¯.
> 4)  Find π(Berri-UQAM) for the original walk. One way to do this is by
>     solving the eigenvalue problem πP = π, taking care to get the left
>     eigenvector corresponding to eigenvalue 1. Compare this
>     probability to that for the other two walks considered here.
>     Comment also on how quickly the limiting probability is approached
>     in the three walks.

# Likelihood function: 
$$
L( \theta ) =\prod ^{T}_{t=1}\prod _{-c\leqslant j\leqslant c;\ j\neq 0} P( w_{t+j} |w_{t} ;\theta )
$$

The symbols and their meaning:
1. $\theta$: The parameter that is learned. Here refers to the vector embeddings of each word.
2. $t$: The variable that represents each word index in the corpus of text. There are $T$ number of words in the corpus.
3. $c$: The size of the window of context
4. $j$: The variable that represents the context words index.
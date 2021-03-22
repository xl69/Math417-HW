$\textbf{Exercise 1.1.1}$ Given functions $\sigma : A\rightarrow B$ and $\tau:B\rightarrow C$, prove that if $\tau\circ\sigma$ is injective, then so is $\sigma$.

$\sigma: A\rightarrow B, \tau : B \rightarrow C \implies  \tau\circ \sigma: A\rightarrow C.$

$\tau\circ \sigma$ is injective $\implies$ $\forall a_1,a_2\in A$, if $\tau\circ \sigma(a_1)=\tau\circ \sigma(a_2)$, then $a_1=a_2\implies$ $\forall a_1,a_2\in A$ if $\tau( \sigma(a_1))=\tau( \sigma(a_2))$, then $a_1=a_2$

$\forall a_1,a_2\in A$, $\sigma(a_1)=\sigma(a_2)\implies \tau( \sigma(a_1))=\tau( \sigma(a_2))\implies a_1=a_2$

We conclude that $\forall a_1,a_2\in A$, if $\sigma(a_1)=\sigma(a_2)$, then $a_1=a_2$. Hence, $\sigma$ is injective.

$\textbf{Exercise 1.2.2}$ Decide which of the following are equivalence relations on the set of natural numbers N. For those
that are, prove it. For those that are not, explain why.

1. $x\sim y$ if $\lVert x-y \lVert \leq 3$

   - $\forall x\in \mathbb{N}$, $ \lVert x-x \lVert=0\leq 3\implies x\sim x\implies\textbf{reflexive}$

   - $\forall x,y\in \mathbb{N}$, $ \lVert x-y \lVert =  \lVert -(x-y) \lVert =  \lVert y-x \lVert \leq 3$

     Hence, $x\sim y \implies y\sim x.$ $x\sim y$ is $\textbf{symmetric}$.

   - Suppose $x = 5, y = 4, z = 1$,  then $\lVert x-y \lVert = 1\leq 3$ and $\lVert y-z \lVert = 3 \leq 3$, but $\lVert x-z \lVert =4 > 3$

     Hence, there exists some $x,y,z\in \mathbb{N}$ such that $x\sim y= \lVert x-y \lVert\leq 3, y\sim z= \lVert y-z \lVert \leq 3$, but $\lVert x-z \lVert > 3$

     $\implies \textbf{Not transitive}$

   We conclude that $x\sim y$ is not a equivalence relation.

2. 
3. 


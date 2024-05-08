[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Claim: if $A$ and $B$ are two graphs with the same number of nodes and are completely connected, they are isomorphic


Since $A$ and $B$ have the same number of nodes let the set of vertices $V_a$ = $V_b$ = {$v_1$, $v_2$, ..., $v_n$}.

Since $A$ is completely connected, for every pair of vertices $v_x$, $v_y$ that exists in $V_A$
where $x \neq y$, there exists an edge that connects these vertices. Since B is also completely 
connected, the same applies for $V_B$

Let $f: V_1 \rightarrow V_2$ be defined as $f(v_x) = v_x$ for all $x$ from 1 to $n$.

$f$ is a bijection because each vertex in $V_A$ maps to a vertex in $V_B$


Since every node is connected to every other node in graph $A$, and the same holds true for graph $B$,
we have satisfied the conditions for isomorphism.

Therefore, since graphs A and B have the same number of nodes and are completely connected, they must be isomorphic.

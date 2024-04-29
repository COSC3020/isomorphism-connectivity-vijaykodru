[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

To prove that two graphs are isomorphic and not completely connected, let's consider two graphs:

Graph G1 with vertices {1,2,3} and edges {(1,2),(1,3)}.

Graph G2 with vertices {A,B,C} and edges {(A,B),(A,C)}.

Looking at the edges in the graphs we can say that these graphs are not completely connected as there is no edge from 2 to 3 in G1 and no edge between B to C in G2. Now, if we map the vertices of G1​ to G2​ such that f(1)=A, f(2)=B, and f(3)=C, this establishes a bijection between the vertex sets of G1 and G2​, satisfying the condition for isomorphism. Additionally, this mapping preserves the edges, as (1,2) maps to (A,B) and (1,3) maps to (A,C), maintaining the same correspondence between edges. Therefore, the graphs G1​ and G2 are isomorphic despite not being completely connected. 

Reference:

https://www2.math.upenn.edu/~mlazar/math170/notes05-2.pdf
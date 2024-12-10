# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

A and B have the same number of nodes, we will call this number n  
One to one function means that every node in A maps to a unique node in B  
We can label every node in each graph as A<sub>1</sub>, A<sub>2</sub> ... A<sub>n</sub>, and B<sub>1</sub>, B<sub>2</sub> ... B<sub>n</sub>  
We can prove that a one to one and onto function exists by matching A<sub>x</sub> to B<sub>x</sub>, with x being the number given from 1 to n. Since n is equal for both, there is the same amount of A<sub>x</sub>s and B<sub>x</sub>s. This means that there is a unique node pairing for every node in A to every node in B, and every node in A is paired with a node in B, as well as the vice versa of both of those. Therefor one to one and onto.
Now we must show our function preserves each edge  
In a completely connnected graph, every node has an edge between itself and every other node, we will call these edges (A<sub>x</sub>, A<sub>y</sub>), where x and y are both values from 1 to n and are not equal.
since in graph A, every node A<sub>x</sub> has n-1 edges, (A<sub>x</sub>, A<sub>y</sub>) where x and y are both values from 1 to n and are not equal, and in graph B, every node B<sub>x</sub> has n-1 edges, (B<sub>x</sub>, B<sub>y</sub>) where x and y are both values from 1 to n and are not equal, and we know that for every A<sub>n</sub> we have exactly one unique corresponding B<sub>n</sub>, we can replace all A<sub>x</sub>s and A<sub>y</sub>s with their corresponding B<sub>x</sub>s and B<sub>y</sub>s, to show that for every (A<sub>x</sub>, A<sub>y</sub>) when we apply our one to one onto function to each of the vertices, (B<sub>x</sub>, B<sub>y</sub>) is created and exists in graph B, with the vice versa being true.

all work is my own

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

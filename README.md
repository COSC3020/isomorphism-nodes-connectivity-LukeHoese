# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

disecting the formal definition can give us a great start to proving that two completely connected graphs with the same number of nodes are isomorphic. G1 = (V1, E1) and G2 = (V2, E2) are the two graphs being checked for isomorphism, and are defined to be tuples of sets of all their vertices and all their edges. The first rule for finding isomorphism is ensuring that both graphs have the same amount of vertices. We already know this as our problem states such. This means we can fulfill the next part of our definition, as with an equal number of nodes we can ensure that there is a one to one and onto bijection such that V1 -> V2. What this means is that for every vertex in graph 1 there is only one vertex corresponding to it in graph 2, and that for every vertex in graph 1 there is a corresponding vertex in graph 2, and the vice versa must be true. Once again knowing that we have the same amount of vertices means this condition is fulfilled. $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$. is the tricky part to explain/understand for me at least, but i will try my best. (u,v) denotes an edge as a pair of vertices. The formal definition tells us that our graphs are isomorphic if for every (u,v) edge in our list of graph 1 edges (E1), when we apply our bijection function to our vertices, giving us the vertices (f(u),f(v)), that this pairing is also an edge in G2. So, if our graphs are completely connected as stated in the problem, meaning every vertex is connected by an edge to every other vertex, and we have the same amount of vertices as stated by the problem, then we know we have the same amount of edges. And we know that every V1 has a corresponding V2, so if they are both fully connected then we should see it hold true that every (u,v) is preserved when mapping to (f(u),f(v)), because there is a one to one and onto relationship between vertices and every possible unique edge is guaranteed to exist for each graph.

that is a whole nightmarish word salad and I hope it makes sense, because I do feel like I genuinely understand it after spending some time on this problem

all work is my own

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

# Problem Statement

Given an undirected graph $G = (V,E)$, and a cost function on vertices $c: V \to \mathbb{Q}^+$, find a minimum cost *vertex cover*, i.e., a set $V' \subseteq V$ such that every edge has at least one endpoint incident at $V'$. The special case, in which all vertices are of unit cost, will be called the *cardinality vertex cover problem*.
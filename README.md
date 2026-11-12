# KarateClub_Modularity-graph
Recursive spectral modularity partitioning on Zachary's Karate Club graph (DSC212). Builds B = A − kkᵀ/2m, splits communities by the leading eigenvector until λ₁ ≤ 0, and recovers the real club split for 33/34 members (Q = 0.409, 5 communities). Tracks centrality and clustering across splits. Python, NumPy, NetworkX.

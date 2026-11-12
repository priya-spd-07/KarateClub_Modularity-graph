<<<<<<< HEAD
# Modularity on the Karate Club Graph (DSC212)

Recursive spectral modularity partitioning (Newman, 2006) on Zachary's Karate Club network,
with per-split visualisations and node-metric evolution (degree, betweenness, closeness, clustering).

## Run
```
pip install -r requirements.txt
jupyter notebook karate_modularity.ipynb      # Kernel -> Restart & Run All
```
The notebook has no external data files: the graph comes from `networkx.karate_club_graph()`.

## Files
* `karate_modularity.ipynb` – code, outputs, figures, discussion
* `requirements.txt` – Python dependencies

## Reference
M. E. J. Newman (2006), *Modularity and community structure in networks*, PNAS 103(23):8577–8582.
=======
# KarateClub_Modularity-graph
Recursive spectral modularity partitioning on Zachary's Karate Club graph (DSC212). Builds B = A − kkᵀ/2m, splits communities by the leading eigenvector until λ₁ ≤ 0, and recovers the real club split for 33/34 members (Q = 0.409, 5 communities). Tracks centrality and clustering across splits. Python, NumPy, NetworkX.
>>>>>>> a7cb712461e126fbb4fe3666a993b40298c9e7c6

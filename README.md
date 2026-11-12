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

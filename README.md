# Pan cancer resilience
This repo contains code to simulate removal of genes from consensus interactome and compute the resilience with several removal schems, including random removal and targeted removal (targeting high degree or highly mutated genes first)

# Content
The consensus interactome is `edge_list_union_all.txt.zip` compressed for memory reason. The pan-cancer mutation data are in `varible_mb_pancancer` in decreasing order from high mutation rate.
All code necessary to compute the resilience with different mutation scheme is present in the jupyter notebook, subdivided with specific functions each of them specialized 
with its own removal scheme. 

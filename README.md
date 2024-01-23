# Simple-kNN-Gzip

Simplistic Linear & Multiprocessed approach to sentiment analysis using Gzip Normalized Compression Distances with k nearest neighbors.

Original work that this concept is based on: https://aclanthology.org/2023.findings-acl.426.pdf
Paper authors also have implementation code here: https://github.com/bazingagin/npc_gzip

They have achieved a higher accuracy than I have, on a separate dataset, but it appears there's something interesting and useful about this methodology.

Ken Schutte also has a couple writeups, explaining at least 2 of the major issues with the original paper:

1. k=2 tiebreaker issue: https://kenschutte.com/gzip-knn-paper/
2. Dataset test leakage (test data was also in the training data): https://kenschutte.com/gzip-knn-paper2/

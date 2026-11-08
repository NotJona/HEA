# Code for The seed-word conundrum: there is no such thing as too much contemporary influence for inferring historical emotion semantics of words

# Abstract
In this contribution we induce historical Valence-Arousal-Dominance (VAD) lexica from static word embeddings and contemporary emotion lexica. We extend prior work with additional embedding and induction algorithms, a second contemporary seed lexicon, and varying seed lexicon size. Against expectations, larger seed lexica did not hurt performance. Five of the six best-performing models yield nearly identical results despite differing in algorithm, embedding, and seed words, suggesting that lexicon size matters more than configuration. Yet our best models still fall short of the correlations between contemporary lexica and historical gold data, raising serious doubts about the approach in its current form. Tracing this contradiction partly to the gold data's own limitations, partly to the limitations of static word embeddings, we argue for a larger, more robust, token-based historical VAD resource going forward.

# Instructions
See main.ipynb for model-setup, execution and results.
See visualizations.ipynb for figures found in the paper.

# Notes:
The processed corpus and large embeddings had to be excluded due to data storage limitations. 
The 1830's section of the COHA is not included - it does not belong to us.

# Predict rna secondary structure based on canonical correlation analysis

The goal is to learn a shared representation of sequence and structure features using canonical correlation analysis.
The secondary structure is predict for a given sequence by finding among the set of suboptimal structure the one minimizing the distance to the sequence in the shared representation. Cosine distance is used to compare sequence and structure representation. Sequence and structure features are given by computing respectively kmers and nmotifs.


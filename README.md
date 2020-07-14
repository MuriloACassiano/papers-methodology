# papers-methodology
## Here I deposit some codes used to make some analyzes in my articles, as well as some explanations to make their use easier and available to the community.


# 'rand_create.ipynb'
The file 'rand_create.ipynb' explains the generation of the negative dataset, used in our submitted article, deposited in bioRxiv:

### Benchmarking available bacterial promoter prediction tools: potentialities and limitations
Authors: Murilo Henrique Anzolini Cassiano and Rafael Silva-Rocha
doi: https://doi.org/10.1101/2020.05.05.079335

We built this code to generate a negative dataset allowing us to assess the available promoter prediction tools’ capacity to distinguish real promoters from random sequences and, because, to the best of our knowledge, there are no experimentally-validated negative promoters datasets available. This code allows its user to generate sequences with a nucleotide distribution similar to that encountered in a given input fasta file (in our case, 865 promoter sequences, present in Regulon DB - see the preprint).

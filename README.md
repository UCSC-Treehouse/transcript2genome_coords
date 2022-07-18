# transcript2genome_coords

This script translates coordinates from transcript space to genome space, requiring only a minimal gtf. It is more flexible about the input format than [transcriptToGenome](https://rdrr.io/github/jotsetung/ensembldb/man/transcriptToGenome.html) in the ensembldb R package, which requires ensembl-specific entries in the gtf.

We developed this script while working on a project that required translating coordinates from FLAIR-generated sample-specific transcripts back to the hg38 genome. 

It takes less than 1 minute to translate 100,000 coordinates using a gene model with 15,000 transcripts. 

The file names are hard-coded; anyone who wants to make the code more robust is welcome to clone the repo. Pull requests are welcome.

# transcript2genome_coords

This script translates coordinates from transcript space to genome space, requiring only a minimal gtf. It is more flexible than tools like [transcriptToGenome](https://rdrr.io/github/jotsetung/ensembldb/man/transcriptToGenome.html) in the ensembldb R package. 

We developed this script while working on a project that required translating coordinates from FLAIR-generated sample-specific transcripts back to the hg38 genome. it takes about 1 minute to translate 100,000 coordinates using a gene model with 15,000 transcripts. 

The file names are hard-coded; anyone who wants to make the code more robust is welcome to clone the repo. Pull requests are welcome.

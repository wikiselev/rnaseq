# nfcore/rnaseq: CCGA Configuration

The IKMB/CCGA Kiel currently maintains one HPC Cluster at Kiel University. 

# CCGA

To run the pipeline with the pre-configured environment, use `-profile ccga`. A full command line call will then look as follows:
```
nextflow run nf-core/rnaseq -profile ccga --reads '*_R{1,2}.fastq.gz' --genome GRCh37 
``` 
---

[![IKMB](images/IKMB_logo.png)](https://http://www.ikmb.uni-kiel.de/)

---

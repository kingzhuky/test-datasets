# test-datasets `eager2`
Test data to be used for automated testing with the nf-core pipelines

## Content of this repository

### Reference genome(s)

`Mammoth_MT_Krause.fasta`: Reference genome for mammoth data.


### Paired-end data

`JK2782_*`: HiSeq MT Capture library (~10K reads after merging, Mammoth Data, Fellows-Yates (2017) Sci. Rep)

### BAM data

`JK2782_*.bam` : Above paired-end data but already merged and mapped to the reference genome.

`JK2067_downsampled_s0.1.bam`: BAM file subsampled from Lamnidis et al. 2018, Nature Communications. Subsampling performed with `samtools view -s 0.2`. Resulting file size 665KB.

# ToDos

- TAD [Trim Align Dedup]
  - Trimming with Cutadapt :heavy_check_mark:
  - Filtering reads aligning to blacklisted regions by aligning with BWA :heavy_check_mark:
  - Alignment with Bowtie2 :heavy_check_mark:
  - Deduplication and MAQ based filtering :heavy_check_mark:
- QC
  - Nreads
    - in a file :heavy_check_mark:
    - in a table
  - FLD :heavy_check_mark:
  - TSS score
  - FRiP
  - Enhancer fraction
  - DHS fraction
  - multiqc report
- Peak calling
  - MACS2
    - option to save qvalue filtered peaks :heavy_check_mark:
    - option to save macs2 pileup *bedgraph* as *bigwig* file :heavy_check_mark:
    - Two-replicates ​
      - IDR :heavy_check_mark:
      - conservative/optimal peaks :heavy_check_mark:
      - rescue ratio/self-consistency ratio :heavy_check_mark:
    - No replicates
  - Genrich :heavy_check_mark:
  - Dfilter
- Peak comparison and annotations
  - Jaccard PCA :heavy_check_mark:
  - ChipSeeker annotations
- Motif finding
  - gimmemotifs
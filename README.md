## Requirments
  1. Data Required
      - Genome file
        - Medicago (v4)
      - Raw data
  2. Softwares Required
      - CellRanger (Used for processing 10x raw data)
      - scanpy  (Used for downstream analysis of 10X data)
      - Seurat (Used for downstream analysis of 10X data)
      - scDblFinder (Used for removing putative doublets)
      - scvi-tools (Used to implement 10X data integration)
      - diffxpy (Used to identify DEGs)
      - edgeR (Used to identify DEGs with replicates)
      - pyscenic (Used for calculating gene set expression score)
      - rpy2 (Used to implement invocation of R packages in python environment)
      - clusterprofiler (Used to perform GO enrichment analysis)

This [jupyter files](notebooks) contains the scripts needed for downstream analysis. Github often fails to preview large jupyter files, You can preview this file using nbviewer. 
The processed data can be accessed at [OMIX database](https://ngdc.cncb.ac.cn/omix/view/OMIX002290)

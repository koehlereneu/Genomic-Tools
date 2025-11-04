# Genomic-Tools

Helpful bioinformatics/genomics tools for future me to use (and maybe someone else too).

## Parse_GFF_GTF

**What it Does**

GFF/GTF files contain dense genomic data that's hard to work with directly. This tool:

- Reads large GFF files efficiently
- Filters out irrelevant features (exons, CDS, etc.)
- Extracts key metadata (gene names, IDs, biotypes) from complex attributes and can be changed according to needs
- Outputs clean dataframes for downstream analysis

### R Version
- Uses `data.table::fread()` for fast file reading
- `dplyr` pipelines for readable data manipulation
- Custom function for attribute field extraction

### Python Version  
- `pandas` for efficient data manipulation
- Vectorized operations for performance
- Flexible attribute parsing with error handling


## FASTA_Quick_Stats
  R Notebook to quickly summarize the contents of a FASTA file — number of sequences, total genome length, GC content, and proportion of ambiguous bases (N's).
 

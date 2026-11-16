# Data, figures and tables: *Tillandsia usneoides* under aged polycarbonate micro-nanoplastic stress

Data, figures and tables of the article "Whole-tissue transcriptomics of the epiphyte *Tillandsia usneoides* under aged
polycarbonate micro-nanoplastic stress reveals a plant-mycobiota response" (submitted to BMC Plant Biology).

Raw reads: NCBI SRA, BioProject [PRJNA1489251](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1489251).

| Path | Content |
|---|---|
| `data/assembly/tillandsia_trinity_cdhit.fasta.xz` | De novo assembly (Trinity, redundancy-reduced with CD-HIT): 506,855 transcripts |
| `data/differential_expression/edgeR_all_tested_features.tsv.gz` | Differential expression (edgeR v4.3.2, likelihood ratio test) for all 124,964 tested features; the 11,075 DETs have FDR < 0.05 and \|log2FC\| > 1 |
| `data/counts/requantification_featureCounts_fraction.tsv.gz` | Read counts of the re-quantification used for the sensitivity analyses (HISAT2 v2.2.1, featureCounts v2.0.6 `-M --fraction`); libraries CMT1-3 (control) and PC1-3 (aPC) |
| `figures/` | Figures 1-4 |
| `tables/` | Table 1 |
| `additional_files/` | Additional files 1-25, numbered as in the article |

Licence: CC BY 4.0 (`LICENSE-DATA`).

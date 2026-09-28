# Data availability and reproduction

## What is included

- Portfolio summaries of two completed coursework reports.
- Fourteen unchanged images extracted from the supplied PDFs, with page-level provenance in `results/figure_provenance.json`.
- A 376-residue FOXL2 sequence transcribed from Coursework 2 page 2; sequence length and amino-acid alphabet checked.
- Selected historical outputs in `results/reported_results.json`, distinguished by evidence type.

This repository has no executable analysis pipeline or claimed clean-environment rerun. Reading it requires only Markdown and image support.

## What is needed to reproduce the original analyses

| Analysis | Additional material required |
| --- | --- |
| TFAP2B alignment | Original FASTA inputs, tool/version, scoring matrix, gap penalties and full alignment summary |
| RNA-seq | Six original count tables, sample metadata, Galaxy history/workflow export, DESeq2 version, design formula, contrast and complete result table |
| BCL11A annotations | Genome browser session or track exports, genome assemblies, GENCODE releases and transcript lists |
| BCR read inspection | Original BAM/BAI, reference assembly, per-site allele/read-quality evidence and relevant IGV session/settings |
| FOXL2 model comparison | Original template/model coordinate files, SWISS-MODEL jobs and alignments, PyMOL commands/selections and MolProbity input/output files |
| Functional enrichment | STRING settings and exports, submitted gene lists, background set, and original enrichment result tables including adjusted p-values |

The figures are sufficient to document selected historical outputs, but not to reconstruct every result. Repeating web-server searches now would be a new analysis, since databases and tool versions can change.

## Source handling

The original PDFs are kept outside this repository. This portfolio omits full teaching prompts, student identification and staff contact details. Software and database content retains its original attribution; no new licence for third-party content is asserted.

Documentation and consistency review used AI assistance. Changes are editorial and explicitly labelled. The original PDFs were not modified.

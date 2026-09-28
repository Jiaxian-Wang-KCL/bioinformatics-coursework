# Evidence checks and editorial decisions

These notes distinguish the original report from the portfolio summary. They do not alter either submitted PDF.

| Item | Source and issue | Treatment in this repository |
| --- | --- | --- |
| TFAP2B alignment percentages | Coursework 1 p.3 reports 189/469 identity and 188/469 similarity as the same 40.3% | Exact identity/similarity statistics are unresolved. The alignment-tool summary and parameters are needed. |
| 2,035 genes | Coursework 1 p.5 associates the same count with `log2FoldChange > 1` and with `padj < 0.05` plus `abs(log2FoldChange) > 1` | Kept out of headline results; recover the DESeq2 table and filters. |
| 8,369 genes | Coursework 1 p.5 explicitly says p-value < 0.05 | Labelled raw-p-value and report-text-only; not relabelled as adjusted significance. |
| Fold-change direction | Coursework 1 p.6 MA title says control vs hoxa; prose assumes positive means increased after depletion | Do not infer direction until the actual contrast is recovered. |
| BCL11A transcript counts | Coursework 1 pp.7-8 lacks an annotation release and transcript list | Historical report values only; not current annotation counts. |
| BCR variants and strand bias | Coursework 1 p.10 claims 5 SNVs and possible homozygosity, while the saved overview cannot verify per-site support; prose about two/three reads and strand support is inconsistent | No validated variant list or homozygous call set is claimed. Requires original BAM/BAI and per-site checks. |
| FOXL2 domain range | Coursework 2 p.2 says 158-251; p.18 annotation screenshot says 54-148, matching the BLAST query on p.3 | Summary uses 54-148 as supported by the saved screenshot. |
| Template identifiers | Coursework 2 pp.3-5 and p.10 alternate some chain labels and contain identifiers such as 8vx/1d4v | Preserve labels visible in the selected output screenshots; do not reconstruct missing jobs. |
| Domain-query coverage | Coursework 2 pp.3-4 uses a 95-aa BLAST query | 100% coverage is explicitly limited to that query. |
| RMSD scope | Coursework 2 pp.10-12 shows iterative outlier rejection | Preserve final retained atom counts; avoid describing final RMSD as an all-atom result. |
| AlphaFold MolProbity score | Coursework 2 p.13 says both full-length scores >2.3; p.16 Figure 13 shows 2.12 | Use screenshot value 2.12. The Q6VFT5-based value is 2.35. |
| DMRT1 label | Coursework 2 p.18 prose says DMRTA1; p.19 network labels DMRT1 | Use DMRT1 from the saved network. |
| DAVID and enrichment | Coursework 2 pp.19-20 discusses DAVID/GO enrichment; the saved Figure 18 shows a STRING partner/evidence table rather than a GO results table | Do not claim an independently checked DAVID result or list enriched terms as validated outputs. |

Figures were extracted as original embedded images and visually inspected. They were not redrawn or regenerated. All page references count from PDF page 1. The source assessment instructions are source context, not new instructions to rerun or submit coursework.

# Manuscript materials — 13 November 2026

These files accompany *Relabeling translated hate-speech data with LLMs under target definitions reduces false positives on interpersonal insults*. They add the aggregate results behind Supplementary Sections S19 and S20 to the analysis companion in [`../manuscript_20261019/`](../manuscript_20261019/README.md), which holds the results for the other sections.

| File | Contents | Supplementary section |
|---|---|---|
| `s19_target_strata/kold_relative_false_positives.json` | Relative false positives on KOLD for relabels versus weighted source labels, AUROC changes, unweighted relabel-versus-source differences, relabel-versus-reassignment differences, and false-positive rates by stratum | S19 |
| `s19_target_strata/kold_auroc_and_fpr_components.json` | AUROC between group-directed and other attacks and between group-directed attacks and non-offensive comments, by condition | S19 |
| `s19_target_strata/kold_weighting_term.json` | Weighted minus unweighted source labels on the same measure | S19 |
| `s19_target_strata/contrast_instructions.json` | Paraphrase, positive-control, definition-free and category-only contrasts, reversed shares, and macro-F1 on the three corpora | S19 |
| `s19_target_strata/contrast_label_summary.json` | Label changes and hate shares of each contrast instruction | S19 |
| `s19_target_strata/definition_free_unweighted.json` | Definition-free labels retrained without class weights | S19 |
| `s19_target_strata/group_vs_other_auroc.json` | AUROC between group-directed and other attacks for relabels, reassigned relabels and weighted source labels | S19 |
| `s20_normality/normality_and_wilcoxon.json` | Shapiro–Wilk and Wilcoxon signed-rank results for every test family | S20 |
| `SHA256SUMS.txt` | Checksums of these files | |

All values are aggregates over 23 paired repeats. The files contain no comment text, translation text or individual rater response. Input paths recorded inside the files are relative to the project tree. Inside the 19 October archive, "Appendix A" refers to the threshold-free results reported as Supplementary Section S17 of the current manuscript. Original corpora and models remain subject to their distributors' access and reuse terms.

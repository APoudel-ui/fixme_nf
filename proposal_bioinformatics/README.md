## Phylogenetic Analysis of *Lactobacillus* spp. Using nf-core/phyloplace Pipeline

```mermaid
flowchart TD
    A["Start: 10 FASTA search of Lactobacillus (HMMER)"] --> B["Sequence Alignment (HMMER / Clustal Omega / MAFFT)"]
    B --> C["Phylogenetic Placement (EPA-NG)"]
    C --> D["Summary and Grafting (GAPPA)"]
    D --> E["Visualization (Heattree)"]
    E --> F["QC Report (MultiQC)"]
    F --> G["End: Final Output - Phylogenetic Tree & Summary Reports"]

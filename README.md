## ANALYSIS ON A Genomics Dataset




download the datset : https://www.ncbi.nlm.nih.gov/datasets/genome/


cbi_dataset/
ncbi_dataset/

|── data/
|-----GCF_000001405.40/
│   ├── sequence_report.jsonl
│   ├── GCF_000001405.40_GRCh38.p14_genomic.fna
│   ├── GCF_000001405.40_GRCh38.p14_genomic.gff
│   ├── GCF_000001405.40_GRCh38.p14_genomic.gtf
│   ├── GCF_000001405.40_GRCh38.p14_genomic.gbff
│   └── dataset_catalog.json


these converted to csv so csv

link for the cleaned dataset > https://drive.google.com/file/d/1j7u2Tjz2arUgWC9tWNVltFSGmGJSIWt4/view?usp=sharing


🧬 Advanced Genomic Feature Analysis: Regulation, Conservation, and Disruption
This project investigates how multiple genomic signals shape gene function, stability, and evolutionary patterns across 12,000+ genes. It combines:

GC Content & Epigenetics

Built a composite epigenetic_score using methylation + GC data

Used regression to explain expression variance (R² ≈ 0.78)

Structural Variation Impact

Mapped SVs (deletions, duplications) to gene locations

Created SV_disruption_score, showing 24% expression drop in affected genes

TFBS Density & Functional Clustering

Calculated TFBS density in 1kb promoter regions

Clustered genes with >50 binding sites into functional modules via k-means and GO enrichment

Evolutionary Conservation of High GC Genes

Compared dN/dS ratios for top 20% GC content genes

Found overrepresentation in DNA repair, chromatin organization, and core regulatory pathways

📊 Tools & Techniques:
Languages: Python, Pandas, Biopython

Models: Linear Regression, Decision Trees, K-means Clustering

Visualizations: Heatmaps, Feature Importance Charts, GO Enrichment Bar Graphs

📌 Key Results: Identified high-impact gene clusters linked to genome stability, essential cellular functions, and transcriptional regulation.

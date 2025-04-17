📘 Project Background:
Non-alcoholic fatty liver disease (NAFLD) and its more severe form, non-alcoholic steatohepatitis (NASH), are among the leading causes of chronic liver diseases globally. A small but significant proportion of patients with NASH eventually develop hepatocellular carcinoma (HCC), the most common type of primary liver cancer.
Understanding the molecular mechanisms and identifying robust gene expression biomarkers that distinguish normal, NAFLD/NASH, and cancerous liver tissues is critical for early detection and preventive intervention.
🧭 Objective:
To perform a comparative gene expression analysis using publicly available datasets (GSE66676, GSE136380, and GSE182060) to identify differentially expressed genes (DEGs), signaling pathways, and potential biomarkers associated with the progression from NAFLD/NASH to liver cancer.
📌 Instructions:
    📂 Dataset Preparation:
        Use the provided GSE66676, GSE136380, and GSE182060 notebooks to load and preprocess the data.
        Ensure that all samples are properly labeled based on condition (e.g., Control, NAFLD, NASH, HCC).
    🧬 Differential Expression Analysis:
        For each dataset, perform statistical tests (e.g., limma, DESeq2-style) to identify DEGs between:
            Normal vs. NAFLD/NASH
            NAFLD/NASH vs. HCC
        Use volcano plots and heatmaps to visualize significant genes (adjusted p-value < 0.05, |log2FC| > 1).
    🧠 Functional Enrichment:
        Perform GO and KEGG enrichment analysis on top DEGs to reveal affected biological pathways.
        Highlight inflammation, fibrosis, metabolic, or oncogenic signaling if present.
    🧬 Cross-Dataset Integration:
        Compare DEGs across the three datasets to identify commonly upregulated or downregulated genes in cancer progression.
        Use Venn diagrams to visualize overlaps.
    🎯 Candidate Biomarker Identification:
        Select a subset of genes showing consistent patterns (e.g., upregulated in NAFLD→NASH→HCC).
        Validate potential biomarkers against publicly known cancer gene databases (e.g., OncoKB, GeneCards).
    📊 Model Building (Optional):
        Use machine learning (e.g., Random Forest, SVM, LASSO) to classify samples based on gene expression profiles.
        Evaluate model accuracy, precision, recall, and ROC-AUC.
    📎 Documentation:
        Summarize key findings: top DEGs, enriched pathways, candidate biomarkers.
        Provide plots, tables, and interpretation in a final report or notebook cell.
📈 Expected Outcome:
    A list of potential genes that act as early biomarkers of malignant progression.
    A comparison of molecular signatures between pre-cancerous and cancerous fatty liver samples.
    Biological insights into pathways involved in NAFLD-related HCC.

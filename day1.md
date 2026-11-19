# Day 1: Blood gene expression in parkinson's disease

Date: 19 Nov 2026

 What I did
- Learned how the research cycle works and the types of bioinformatics research
- Narrowed a broad area into a specific topic using the "funnel" method
- Searched GEO (NCBI) for public Parkinson's disease datasets
- Learned how to check whether a dataset has both patient and control samples

Topic funnel
- Area: Neurodegenerative disease (Parkinson's disease)
- Sub-area: Blood gene expression
- Problem: Finding gene expression differences between PD patients and healthy controls
- Dataset: GSE290333 (PBMC, Affymetrix Clariom S microarray, PD vs controls, 38 samples after QC)

 Why this dataset
- Public and free to access
- PD and control groups present
- Drug-naive patients, so no medication effect
- Microarray data is beginner-friendly (limma / GEO2R)
- Recently released, so likely less explored

What I learned
- GEO search results show many databases; GEO DataSets is the one for expression data
- Check Summary, Overall design, and Samples/Characteristics to confirm groups
- Total sample count is not the same as patient count

 Next
- Day 2: literature search, to find out what has already been done with this dataset

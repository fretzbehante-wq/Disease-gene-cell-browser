
# UCSC Cell Browser Disease-Gene Lab Activity

## Assigned Gene and Disease

**Gene:** COL1A1  
**Associated disease:** Osteogenesis imperfecta (OI)

COL1A1 encodes the alpha-1 chain of type I collagen, an important structural protein in connective tissues. Variants in this gene can affect collagen production or structure and are associated with osteogenesis imperfecta.

## PART B. Dataset Selection and Relevance

**Dataset name:** Aging Human Skin  
**Study title:** *Single-cell transcriptomes of the human skin reveal age-related loss of fibroblast priming*  
**Study authors:** Solé-Boldo et al.  
**Tissue:** Human skin  
**Cell data:** Approximately 15,457 visible cells, as displayed in the Cell Browser.

This dataset was selected because it contains human skin cells, including fibroblast-related populations. Since COL1A1 is involved in type I collagen production, this dataset provides a relevant way to examine its expression across different cell populations.


## PART C. Understanding the Cell Map

**1. What type of visualization does the UCSC Cell Browser use?**

The Cell Browser uses a two-dimensional cell map to display cells in groups called clusters.

**2. What does each point represent?**

Each point represents an individual cell. Cells positioned near one another generally have similar gene-expression profiles.

**3. What do the clusters represent?**

Clusters represent groups of cells with similar characteristics or gene-expression patterns. The dataset includes Mesenchymal, Secretory-reticular, Pro-inflammatory, Differentiated Keratinocytes, Vascular EC, T cells, and other annotated populations.

## PART D. COL1A1 Expression Distribution

**1. How is COL1A1 expression distributed across the cell map?**

The expression map shows variation in COL1A1 expression among the cells. The color legend indicates different expression levels, allowing the distribution of the gene to be examined across the annotated populations.

**2. Which cell types show stronger or weaker expression?**

The map displays differences in expression intensity across the cell populations. The exact strongest and weakest populations should be identified from the displayed colors and expression values rather than assumed from the cluster names alone.

## PART E. Cell Types and Biological Interpretation

**1. Which cell types appear to be associated with COL1A1 expression?**

The dataset contains several skin cell populations, including Mesenchymal and Secretory-reticular cells. The marker-gene results identify COL1A1 as a top marker of the Mesenchymal cluster.

**2. Is COL1A1 broadly expressed or restricted to one cell type?**

The expression map should be used to determine whether COL1A1 is distributed across multiple cell populations or is more concentrated in particular groups. The available marker table supports a strong association with the Mesenchymal cluster, but it does not establish that expression is exclusive to that cluster.

**3. What is the biological significance of the observed pattern?**

COL1A1 contributes to type I collagen production and extracellular matrix structure. Its association with the Mesenchymal cluster is biologically relevant because mesenchymal cells are involved in connective-tissue functions. However, these observations describe the selected dataset and do not prove that COL1A1 is expressed only in mesenchymal cells.

## PART F. Comparing Gene Expression Using a Dot Plot

**1. What does the dot plot show?**

The dot plot compares the expression of several genes across different cell populations.

- **Dot size:** Proportion of cells expressing the gene.
- **Dot color:** Average gene expression, according to the plot legend.

**2. What additional information does the dot plot provide?**

The dot plot summarizes expression across cell populations, making it easier to compare patterns than viewing individual cells alone. It includes COL1A1 and other genes, allowing their expression patterns to be examined across the annotated groups.

## PART G. Cluster Marker Genes

**1. Which cluster did you examine?**

- **Selected cluster:** Mesenchymal

**2. What are the top three marker genes displayed for this cluster?**

| Marker gene | Approximate Z-score |
|---|---:|
| COL1A1 | 52.19 |
| COL1A2 | 50.17 |
| COL3A1 | 40.70 |

**3. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.**

Yes, COL1A1 appears as a top marker of the Mesenchymal cluster in the displayed marker table. However, this does not mean that the gene is exclusive to this cluster or that it is a universal marker in every tissue.

## PART H. Comparing COL1A1 With One Marker Gene

**1. What is your assigned disease gene?**

- COL1A1

**2. Which marker gene did you choose for comparison?**

- COL1A2

**3. Which gene shows a more cell-type-restricted expression pattern? Which appears more broadly expressed?**

Both genes appear among the top markers of the Mesenchymal cluster. Their relative expression across other cell populations should be compared directly using the gene-expression plot before determining which is more restricted or broadly expressed.

**4. What does this comparison teach you about a disease-associated gene and a cell-type marker?**

A disease-associated gene is linked to a particular disease through its biological function or genetic variants, while a cell-type marker helps identify or distinguish a cell population. A gene can serve both roles, but its presence in a marker list does not mean it causes a disease.

## PART I. Connecting the Cell Browser to the Previous Genome Activity

**1. On which chromosome is COL1A1 located?**

- Chromosome 17 in the human reference genome.

**2. What disease-associated variant did you examine previously?**

- **Variant:** NM_000088.4(COL1A1):c.1678G>A (p.Gly560Ser)
- **ClinVar Variation ID:** 265433
- **Previously recorded classification:** Pathogenic

**3. Which cell types express COL1A1 in the current dataset?**

The dataset allows COL1A1 expression to be examined across annotated human skin cell populations. The expression map and dot plot should be used to identify the specific populations showing detectable expression.

**4. Does the observed expression make biological sense based on the gene's function?**

Yes, the association of COL1A1 with the Mesenchymal cluster is consistent with its role in collagen production and extracellular matrix structure. The dataset provides a cellular context for studying this gene in human skin. However, expression patterns may vary among cell populations and should be interpreted using the actual plot results. The expression data do not directly show the effect of the previously examined variant.

**5. Can this single Cell Browser dataset prove that COL1A1 causes osteogenesis imperfecta? Why or why not?**

No. The dataset shows gene-expression patterns in human skin cells, but it does not establish that a specific genetic variant causes osteogenesis imperfecta. Additional genetic, clinical, and functional evidence is needed to establish disease causation.

## PART J. Short Reflection

**1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**

The Cell Browser allowed me to examine COL1A1 expression across different cell populations. In contrast, the Genome Browser helped me investigate the gene's genomic location, structure, and associated variant.

**2. Why can the same gene have different expression levels among different cell types?**

Different cell types perform different functions and therefore activate different sets of genes. Gene expression can also vary with cell state, age, and environmental conditions.

**3. Why should you be careful when interpreting zero or very low expression in single-cell data?**

Zero or low expression does not always mean that a gene is completely inactive in a cell. Some transcripts may not be detected because of technical limitations in single-cell sequencing.

**4. Why is it useful to combine genomic location, genetic variants, and cell-specific gene expression?**

These sources provide complementary information about a gene. Genomic location shows where the gene is found, variant information helps identify possible genetic changes, and cell-specific expression provides context about the cells in which the gene is active.

**5. What was the most interesting observation you made about your assigned gene?**

One interesting observation was that COL1A1 appeared as the highest-ranked displayed marker in the Mesenchymal cluster. This is relevant to its role in type I collagen production, although its expression in other cell populations should also be considered.

## References and Links

- Solé-Boldo, L., et al. (2020). Single-cell transcriptomes of the human skin reveal age-related loss of fibroblast priming. *Communications Biology, 3*, Article 188. https://doi.org/10.1038/s42003-020-0922-4
- UCSC Cell Browser. *Aging Human Skin dataset*. [Insert the exact dataset URL]
- National Center for Biotechnology Information. *ClinVar*. https://www.ncbi.nlm.nih.gov/clinvar/

UCSC Cell Browser. (n.d.). *Aging Human Skin dataset*. https://cells.ucsc.edu/?ds=aging-human-skin&label=Celltype&gene=COL1A1 

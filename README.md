# Cell Cycle Data Analysis

The cell cycle is four stage process that describes a cell's growth and replication.

The cell: 
- Increases in size (gap 1, or G1, stage)
- Copies its DNA (synthesis, or S, stage)
- Prepares to divide (gap 2, or G2, stage), and
- Divides (mitosis, or M, stage).

The dataset includes gene names, and its concentration during the G1, S and G2 stages.

The data analysis seeks to answer some questions:
1. Can the concentration of proteins be estimated by the concentration of mRNA?
2. What is the correlation of mRNA and Proteins in all stages?
3. Can any clusters be identified with cell features within the cell cycle stages?
4. Are certain features better at providing estimates than others?

The data analysis seeks to obtain correlations via plotting relevant features against eachother, as well as using k-means clustering for futher investigation.

It was found that most of the correlations were fairly low between mRNA and Protein concentration within the cycles. Therefore it is difficult to estimate concentrations from one stage to another. However:

Certain features within genes, for example, located in the ribosome, provide a far greater correlation. For example, the correlation between G1 mRNA and G1 protein containing ribosomes is 0.84.

Inspect Jupyter Notebook for full details.

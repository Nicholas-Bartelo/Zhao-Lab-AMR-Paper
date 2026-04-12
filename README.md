# Zhao-Lab-AMR-Paper
Repository where all code is stored which was used for the analysis in the paper: Unmasking Carbapenem Resistance Amid Species Variations: An Untargeted Metabolomics Study of Klebsiella pneumoniae and Escherichia coli 

Folders:

1. Data Preprocessing 

Two files are included in this folder: 
1. new analysis with annotated mz only.Rmd - Code used to create all the files in the Output File Foder.
2. 03-18-2026 new analysis with annotated mz only updated PCA.ipynb - Updated code to create the final PCA plots for Figure 2a-d.
Code for preprocessing raw data, the initial metabolomics annotations from refmet and metabolomics workbench, visualizations for Figure 2a-d, and ANOVA testing between batches.

* Input File Folder: Contains the raw input metabolomics matrix, metabolites with an annotation under the 0.01 m/z tolerance, and the organism information for the samples.
* Output File Folder: Contains the results for the pre- and post-batch corrected ANOVA between batches (Supplementary Table 2), processed metabolomics matrix, an non-standardized processed metabolomics matrix.

2. Figure 1

Code for creating the donut plot in Figure 1a as well as png of the figure, the processed metabolomics matrix, and visualization of the flowchart in Figure 1b.

3. Firth Logistic Regression

Code for running firth logistic regression analysis.

* Input File Folder: Contains the  processed metabolomics matrix.
* Output File Folder: Contains the results for firth logistic regression for all organisms (Supplementary Table 4).

4. ML Biomarker Detection

Code for running LogisticRegressionCV to find supervised learning metrics for Escherichia coli and Klebsiella pneumoniae as well as metabolomic biomarkers of resistance.

Code containing statistical analyses and results used to create Figure 4a-f.

* Input File Folder: Contains the  processed metabolomics matrix.

5. Statistical Testing

Code containing statistical analyses and results used to create Figure 3a-c.

* Input File Folder: Contains the processed metabolomics matrix.
* Output File Folder: Contains the results for the univariate two-way anova which tested organism, group, and the interaction between organism and group (Supplementary Table 3).


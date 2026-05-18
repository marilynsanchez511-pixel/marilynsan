## Sickle Cell Disease Gene Expression.
## Group members: Marilyn Sanchez Adorno.
## Project Desc:
using metadata from ncbi to find the difference in gene expression for Sickle Cell Disease (SCD). Identifying upregulated genes by comparing SCD and healthy samples, vizualize global expression with PCA plots. Using these plots to highlight key genes expressed in SCD. 
## Main Question: 
What are the genes that cause the symptoms associated with SCD.
## Data used:
Python libraries needed:
-pandas 
-numpy 
-scipy.stats 
-matplotlib
-klearn.decomposition
https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE102881   
12 samples, 5 SCD and 7 healthy. Around 21 thousand genes per sample. use a p value < 0.01 since FDR doesnt sort it fully. Some of the samples had different areas of extraction and are on drugs which could effect the results of the gene expression. 
#How to run:
Download GSE102881_expressionMatrix_cpm.txt.gz from the link and upload it into your drive account.
Open FinalRealProjectSCD.ipynb in GoogleColab and edit the third comand depeninding where you placed the data.
Then hit "Run all".  


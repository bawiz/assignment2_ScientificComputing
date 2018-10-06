# assignment2_ScientificComputing
Scientific programming course. Assignment 2 about multivariate statistics

# Authors list
Dara Sevkan Akdag. 
Maastricht university Systems Biology M.Sc. 

# Compile and execution suggestions
The jupyter notebook can be executed in your web browser after jupyter notebook has been succesfully installed. Installation guide can be found at: http://jupyter.org/install
The kernel used to execute the notebook is based on an anaconda distribution of python 3. 
Anaconda is a package handler which is great for installing libraries. https://conda.io/docs/user-guide/install/index.html

# Data
The descriptors matrix was computed based on variables from PubChemAid 624202. The study is called "QHTS Assay To Identify Small Molecule Activators Of BRCA1 Expression". Reference:
National Center for Biotechnology Information. PubChem BioAssay Database; AID=624202, https://pubchem.ncbi.nlm.nih.gov/bioassay/624202 (accessed Oct. 5, 2018).

# Pipeline
The pipeline of the notebook is split in 3 main parts.
- Data preparation (removing NaNs and making sure activity scores are associated with the correct descriptor entries)
- Data exploration (Boxplot, heatmap and PCA.)
- Data analysis (PLS with cross validation, Ridge regression, Lasso regression and elastic net).

Next step could be to apply forward feature selection. I did some preliminary feature selection but without any luck, so I removed it from the analysis. 

# Expected output
The expected output can be viewed the the jupyter notebook which is uploaded. 
You should be able to get a descriptor matrix which contain the activity scores. And all analyses should be available once the appropriate libraries are installed.

# Libraries
Pandas http://pandas.pydata.org/pandas-docs/stable/api.html
Numpy  http://www.numpy.org/
Scikit learn packages: http://scikit-learn.org/stable/#
Matplotlib https://matplotlib.org/
Seaborn https://seaborn.pydata.org/

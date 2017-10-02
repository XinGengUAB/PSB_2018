# PSB_2018
# Contact - Arunima Srivastava (srivatava.1@osu.edu)
Contains:


1.) Rscripts and Data files - All data (gene lists, data matrices, functions and methods) to perform multinomial log-linear regression of TCGA BRCA dataset (105 patients).


2.) Modeling_Results_Key_Genes_Proteins_Evidence - Excel File containing tabs for individual results (performance metrics) for Imaging, Transcriptomics and Proteomics models. Details of Gene List overlaps with the data, final comparison between data modalities along with standard deviation of models assessed with cross-validation and independent literature evidence for many of the RFE identified key genes and proteins and the associated cohort


3.) Details of CNN construction - Parameter and structure details of the various version of GoogLeNet employed

4.) Tabulated results from PRECOG analysis  - Results from the PRECOG database (precog.stanford.edu) associating the key predictive genes from the transcriptomics model to clinical outcome in breast cancer

5.) Details of model evalutation - Description of model building and evaluation for proteogenomics and histology image (CNN) based models

6.) Key_Transformative_Features_For_All_CNN_Versions - Description of all 5 versions of CNNs utilized for analyzing tiles of histology images

7.) CNNs_And_Histology_Images - Details on the utility of CNNs as the primary technique in designing classifiers for histology images, along with literature based evidence

####################

Github repositories for implementation of histology image tiling and GoogLeNet housed here:
https://github.com/chaitanya2334/openslide-svs-tiler

https://github.com/chaitanya2334/hist-cnn




Implemented various classification models to predict the the various subtypes of Bone Marrow MPN Disease.
The data is collected from NCBI website.
Step 1 : All individual files containing gene expression values for each subject is combined and lablled with the disease they are suffering from
Step 2 : After merging, the dataset had 402 samples and 26k+ features(as gene expression values)
Step 3 : Carried out Deseq2 analysis to filter out the differently expressed genes
Step 4 : Applied ML classification model to get result.

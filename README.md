# IBM_Advanced_DataScience_Capstone
IBM Advanced Data Science Professional Certificate Capstone project

This is the repo for the Jupyter notebooks developed for my Capstone project for the IBM Advanced Data Science Professional Certificate: "AUTOMATIC DIAGNOSIS OF RESPIRATORY DISORDERS".

A presentation video is available on youtube: https://youtu.be/AKG-gqoK8Cs 

The project aims to classify and predict respiratory disorders from sound data files.
The dataset is described and available on Kaggle: https://www.kaggle.com/vbookshelf/respiratory-sound-database/home 

The notebooks are:
- BNA_Capstone_DataAnalysis_nb.ipynb: initial data analysis,
- BNA_Capstone_Feature_Extraction-v1.0.1.ipynb: initial feature extraction
- BNA_Capstone_Model_ML-v1.0.1.ipynb: initial ML models, using the ouputs from BNA_Capstone_Feature_Extraction-v1.0.1.ipynb
- BNA_Capstone_Feature_Extraction-with_Data_Augmentation_v1.2.ipynb: feature extraction with data augmentation
- BNA_Capstone_Model_ML-v1.3.ipynb: ML models, using the outputs from BNA_Capstone_Feature_Extraction-with_Data_Augmentation_v1.2.ipynb
- BNA_Capstone_Model_DL-v1.3.2.ipynb: DL models, using the outputs from BNA_Capstone_Feature_Extraction-with_Data_Augmentation_v1.2.ipynb

To use the notebooks, you can follow the steps below:
1. Clone this repo
2. Download the "Respiratory Disorder" dataset at:
3. Unzip the zip file to <repo>/dataset/Respiratory_dataset/ (paths are configurable on the notebooks)
4. Edit the file "demographic_info.txt"; the first line should be empty, remove it and save file

You should be good to go!

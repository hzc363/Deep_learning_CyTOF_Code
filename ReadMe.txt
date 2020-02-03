This collection of code allows readers to reproduce the results reported in the paper “A robust and interpretable, end-to-end deep learning model for cytometry data.”  The following Jupyter Notebooks are included, which are should be executed sequentially. 

1) code_01_identify_CyTOF_data.ipynb. The code identified CyTOF data with associated CMV diagnosis from ImmPort database. 
2) code_02_download_CyTOF_data.ipynb. The code downloads the CyTOF data from ImmPort. 
3) code_03_read_fcs_files.ipynb. The code read the fcs files and store them as Numpy arrays. 
4) code_04_preprocessing_data.ipynb. The code pre-process the CyTOF data, including signal transformation and data sub-sampling. 
5) code_05_CyTOF_CMV_diagnosis.ipynb. The code trains a deep CNN model to diagnose CMV infection using CyTOF data. 
6) code_06_permutation_analysis.ipynb. This code use a permutation-based method to identify key cell subset associated with CMV.
7) code_07_flowsom_analysis_R_code.ipynb. This code identifies cell subsets using flowSOM. This code is written in R. 
8) code_08_randomforest_using_flowsom_result.ipynb. This code apply random forrest on the flowSOM result to diagnose CMV. 
9) code_09_CyTOF_CMV_augmented.ipynb. This code test if the deep learning model can be augmented with demographical data to improve the accuracy of CMV diagnosis. 
10) code_10_CytoDx.ipynb. This code test the performance of CytoDx.This is code is written in R. 
11) code_11_CellCNN.ipynb. This code test the performance of CellCNN. 
12) code_12_meta_analysis.ipynb. This code identifies the CD3+ CD8+ CD27- CD94+ cell subset in all 9 studies using metaCyto. This is code is written in R. 

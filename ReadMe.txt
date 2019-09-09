This collection of code allow readers to reproduce the results reported in the paper “A robust and interpretable, end-to-end deep learning model for cytometry data”.  The following Jupyter Notebooks are included, which are best executed sequentially. 

1) code_01_identify_CyTOF_data.ipynb. The code identified CyTOF data with associated CMV diagnosis from ImmPort database. 
2) code_02_download_CyTOF_data.ipynb. The code downloads the CyTOF data from ImmPort. 
3) code_03_read_fcs_files.ipynb. The code read the fcs files and store them as Numpy arrays. 
4) code_04_preprocessing_data.ipynb. The code pre-process the CyTOF data, including signal transformation and data sub-sampling. 
5) code_05_CyTOF_CMV_diagnosis.ipynb. The code trains a deep CNN model to diagnose CMV infection using CyTOF data. 
6) code_06_meta_analysis_R_code.ipynb. This code test if the cell subsets identified in code_05 are associated with CMV infection, using data from all 9 studies. This code is written in R. 
7) code_07_flowsom_analysis_R_code.ipynb. This code identifies cell subsets using flowSOM. This code is written in R. 
8) code_08_test_gating_methods.ipynb. This code test the performance of gating-based method in diagnosing CMV infection. 
9) code_09_CyTOF_CMV_augmented_model.ipynb. This code test if the deep learning model can be augmented with demographical data to improve the accuracy of CMV diagnosis. 
10) code_10_plot_data.ipynb. This code visualize the result from previous codes. 
11) code_11_CyTOF_CMV_permutation.ipynb. This code perform a permutation analysis to test if the computational model in code_5 is robust to the choice of training and testing dataset. 


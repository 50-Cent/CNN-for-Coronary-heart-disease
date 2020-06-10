# CNN-for-Coronary-heart-disease
This work proposed a shallow network with CNN layers to classify patients whether they have coronary heart disease or not based 
on their clinical and demographic attributes. The dataset is in xlsx format. The dataset is highly imbalanced regarding the number of 
patients in each category: Coronary heart disease and no-coronary heart disease.

The following files are in this repository:

1. DNN_HeartDisease.ipynb: This file contains codes for data read, LASSO, sampling, different NN architectures, and some of the state-of-the-art ML models.   

2. CAD_sampling_strategies.ipynb : The file contains codes for the undersampling and oversampling strateggies along with their tSNE embedding.

3. CoronaryHeartDisease.xlsx : This is the dataset containing clinical attributes of almost 37000 patients and the attributes are 
recorded over 16 years. 

If you follow this work, please cite 

Dutta, A., Batabyal, T., Basu, M., & Acton, S. T. (2020). An Efficient Convolutional Neural Network for Coronary Heart Disease Prediction. Expert Systems with Applications, 113408.

Bibfile:
@article{dutta2020efficient,
  title={An Efficient Convolutional Neural Network for Coronary Heart Disease Prediction},
  author={Dutta, Aniruddha and Batabyal, Tamal and Basu, Meheli and Acton, Scott T},
  journal={Expert Systems with Applications},
  pages={113408},
  year={2020},
  publisher={Elsevier}
}


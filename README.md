# Audio-classification
Classification of different audio classes using pytorch.
First you need to download FSDKaggle2018 dataset and put files into the data folder.

1) Audio_data_analysis.ipynb -> Analyses the data distribution
2) Feature extraction.ipynb  -> Extracts features from audio samples
3) Audio_model_training.ipynb -> Creates and trains a deep learning model (CNN-GRU) for classification
4) Audio_model_test.ipynb -> Evaluates the performance on validation set. We calculate the confusion matrix and do a T-Sne plot 
5) Audio_inference.ipynb -> Can be used for classfiying any wav file

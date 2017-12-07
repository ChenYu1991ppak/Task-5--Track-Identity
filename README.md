# Task-5--Track-Identity

This project train a classifier to recongize the track produced by human or mechine.
We use a pipeline which has two components, PCA and SVM, as classifier. The data sets are offered by GeeTest company.

All the commands of running this program as follows:
1. Counting KL of each features:
python3 TrackIdentity.py count-features-KL
2. Drawing scatter that the data dimensionality reduced by PCA:
python3 TrackIdentity.py draw-PCA-scatter
3. Drawing scatter that the data dimensionality reduced by TSNE:
python3 TrackIdentity.py draw-TSNE-scatter
4. Training and predicting the tracks, and reporting the result: 
python3 TrackIdentity.py classify-by-pipeline

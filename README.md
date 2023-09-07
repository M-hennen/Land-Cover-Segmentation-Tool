# Land cover Segmentation
Identifying gold mine sites using segmentation model

Sentinel-2 and Landsat optical data segmentation
This code uses machine learning, through an unsupervised classification model called K-Means clustering (here is a short description https://www.youtube.com/watch?v=4b5d3muPQmA) to classify different surface conditions / land cover types without the need for training data. Classification is based upon the variance within the data in your region of interest.

K-Means is one of the most used algorithms in clustering for its simplicity. It basically divides n observations (pixels values in our case) into k clusters (number of classes predefined by user) where each observation belongs to the cluster with the nearest mean.

The code is designed to work with Sentinel-2 and Landsat data. Using Planetary Computer environments, EO data is sourced from the STAC catalogue and processed in the cloud.

It is designed to be fairly intuitive, and requires only a few inputs to make it work - these are highlighted in the comments.

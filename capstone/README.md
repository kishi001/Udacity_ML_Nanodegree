# Udacity MLND Capstone

Capstone project for Udacity's Machine Learning Nanodegree

## Problem Statement

For this project, we have to detect which species of fish appears on a boat, based on images captured from boat cameras of various angles.
Our goal is to predict the likelihood of fish species in each picture from the given Eight categories: 1. Albacore tuna 2. Bigeye tuna 3. Yellowfin tuna 4. Mahi Mahi 5. Opah 6. Sharks 7. Others (meaning that there are fish present but not in the above categories) 8. No Fish (meaning no fish in the picture). 

Each image has only one fish category, expect that there are sometimes very small fish in the pictures that are used as bait.


## Datasets

The dataset can be downloaded from [The Nature Conservancy Fisheries Monitoring](https://www.kaggle.com/c/the-nature-conservancy-fisheries-monitoring/data)


For this project we have around 4000 images for training and 1000 images for testing captured from boat cameras of various angles.

Eight target categories are available in the dataset
1. Albacore tuna
2. Bigeye tuna
3. Yellowfin tuna
4. Mahi Mahi
5. Opah
6. Sharks
7. Others (meaning that there are fish present but not in the above categories)
8. No Fish (meaning no fish in the picture). 

The dataset was compiled by The Nature Conservancy in partnership with Satlink, Archipelago Marine Research, the Pacific Community, the Solomon Islands Ministry of Fisheries and Marine Resources, the Australia Fisheries Management Authority, and the governments of New Caledonia and Palau.


## Requirements
* Python 3.6
* Jupyter Notebook / Ipython

## Python libraries
* tensorflow
* keras
* matplotlib
* sklearn
* numpy
* pandas
* openCV (cv2)
* seaborn
* tqdm

## Run
* Open `Jupyter Notebook capstone_project.ipynb` in the root folder.
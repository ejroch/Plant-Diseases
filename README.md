# Plant-Diseases
Introduction to Deep Learning Final Project - Classification of Plant Diseases

By: Ethan Rocheleau

For: Final Project Deep Learning

University of Montana

All related project files are located in this repository including the dataset PlantVillage. Mind you the file size is roughly 900 MB because of the nature of there being 50,000 images located in the dataset. 

That being said there are quite a few dependencies/libraries in the jupyter notebook itself. The notebookshould be able to be pulled and run with little to no problems, however, the training process for image training can be an extensive one if you are not leveraging a powerful GPU. Based off of the CPU training for one model could take upwards of 10 hours, so given that be sure that you are using a capable system if you decide to run the training portion of the jupyter notebook.

Dependencies include:

torch
torchvision
cudatoolkit
numpy
torchsummary
matplotlib
sklearn
scikitplot

If you wish to seek out the dataset yourself, there are several PlantVillage dataset variations that can be used. The data set that i used in this project is located here:

www.kaggle.com/datasets/mohitsingh1804/plantvillage

If you download the dataset from the site, splitting the data into 3 appropriate training,validation, and test dataset will need to be done but if you download it from this repository it will already be done for you. That being said data augmentation is done in the jupyter notebook and can be run to confirm this however, due to the large number of images, it might take some time.

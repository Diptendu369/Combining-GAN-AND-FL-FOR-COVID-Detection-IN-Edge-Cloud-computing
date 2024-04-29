# FL-GAN_COVID
This is source code for the paper: "Federated Learning for COVID-19 Detection with Generative Adversarial Networks in Edge Cloud Computing".
# Requirements:
python >=3.5

tensorflow >= 2.6

pytorch >= 0.4
# How to run this code: 
Install all required libraries and now ready to run the code. It is recommended to run the standalone GAN code "COVID_GAN3.py" first, then run the FL-GAN code "Server_COVID.py". Here, we set 1 server and random 50 hospitals as hospital clients for training the COVID X-ray data. Then, using the CNN classifer with the code "CNN_COVID_Classification.py" for COVID detection.

Before running the code create a folder named "dataset_train_new" , create 3 folders named "covid" , "pneumonia" and "normal" in THAT dataset_train_new folder. download the dataset from kaggle (link provided below) . put the x-ray images from kaggle dataset to dataset_train_new according to the name of dieases .
# COVID-19 datasets: 
I've taken the dataset from "https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia"


--------------------------


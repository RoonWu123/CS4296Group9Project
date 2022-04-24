# CS4296GrpProject

This is the source code for Convolutional neural networks in CS4296 Group 9 Project. Both tested and worked on AWS Sagemaker and Google Colab Environment.

The Github Link: 
https://github.com/RoonWu123/CS4296Group9Project

The dataset and the source codes （both Google Colab and Sagemaker） can be found on the following link: 
https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR

# Instruction on the AWS SageMaker

Please head to the https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR?usp=sharing
Download the dataset "CatRabbit.zip"

Then launch a Amazon SageMaker Notebook, select a kernel with TensorFlow module
Due to the limitation of SageMaker notebook cannot upload directories, the directories need to be made manually.

Create a directory named "CatRabbit" manually (or change the source directories at your convenience)
Then create 3 directories named "test-images", "train-cat-rabbit" and "val-cat-rabbit" manually
For train-cat-rabbit and val-cat-rabbit, create 2 directories named "cat" and "rabbit" manually

The overall structure will be like:
root/
├─ CatRabbit
│  ├─ test-images
│  ├─ train-cat-rabbit
│  │     ├─ cat
│  │     └─ rabbit
│  └─ val-cat-rabbit
│        ├─ cat
│        └─ rabbit
└─ CatRabbitCode.ipynb


Then unzip the file on you own local machine and upload the content (images) to directories respectively

# Instruction on the Google Colab

Please head to the https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR?usp=sharing

Download the dataset "CatRabbit.zip" and unzip the content in the zip file and upload it to google drive

Then launch a Google Colab Notebook (default with TensorFlow module)

Mount the google drive after enter the Colab environment
![image](https://user-images.githubusercontent.com/79595031/164977802-7c5186cb-897a-4f8e-a449-cf74ce587447.png)


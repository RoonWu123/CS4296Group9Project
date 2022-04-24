# CS4296GrpProject

This is the source code for Convolutional neural networks in CS4296 Group 9 Project. Both tested and worked on Amazon Sagemaker and Google Colab Environment. <br>
<br>
The Github Link: <br>
https://github.com/RoonWu123/CS4296Group9Project

<br>
The dataset and the source codes （both Google Colab and Sagemaker） can be found on the following link: <br>
https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR

<br>

# Software/hardware dependencies

For both source code, there is no special hardware dependencies as both platforms in free tier will prepare the <b><ins>basic</ins></b> hardware. <br>
However, our project has invoked different instances (AWS) and plans (Colab) to review the performance of two different platforms, <br> so the paid tier will have different hardware supplied. <br>

For software dependencies, we need to invoke the kernel with TensorFlow module. Each Colab notebook that Google provided will contain the TensorFlow module by default.<br>
However, for Sagemaker Notebook, it is required to select the kernel manually in the kernel Selection Page after launching the notebook instance.
![image](https://user-images.githubusercontent.com/79595031/164978895-5faa8e35-8bd1-42fe-8789-976b5da7b580.png)


# Instruction on the AWS SageMaker
<br>
Please head to the https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR?usp=sharing
Download the dataset "CatRabbit.zip"<br>
<br>
Then launch a Amazon SageMaker Notebook, select a kernel with TensorFlow module<br>
Due to the limitation of SageMaker notebook cannot upload directories, the directories need to be made manually.<br>
<br>
Create a directory named "CatRabbit" manually (or change the source directories at your convenience)<br>
Then create 3 directories named "test-images", "train-cat-rabbit" and "val-cat-rabbit" manually<br>
For train-cat-rabbit and val-cat-rabbit, create 2 directories named "cat" and "rabbit" manually<br>
<br>
The overall structure will be like: <br>
root/<br>
├─ CatRabbit<br>
│&nbsp;&nbsp;├─&nbsp;test-images<br>
│&nbsp;&nbsp;├─&nbsp;train-cat-rabbit<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├─&nbsp;cat<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─&nbsp;rabbit<br>
│&nbsp;&nbsp;└─&nbsp;val-cat-rabbit<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├─&nbsp;cat<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─&nbsp;rabbit<br>
└─&nbsp;CatRabbitCode.ipynb<br>
<br>
Then unzip the file on you own local machine and upload the content (images) to directories respectively<br>
The notebook, containing the source code, can now be uploadede to the sagemaker<br>
The data source path may change due to the modification of directories locations
![image](https://user-images.githubusercontent.com/79595031/164978168-fac05a3c-1507-4ed9-97bf-7e90b1fda967.png)
<br>

# Instruction on the Google Colab
<br>
Please head to the https://drive.google.com/drive/folders/14LKnmDwWf1rxjUwgH--nPMgwAXOBhadR?usp=sharing
<br>
Download the dataset "CatRabbit.zip" and unzip the content in the zip file and upload it to google drive<br>
<br>
Then launch a Google Colab Notebook (default with TensorFlow module)<br>
<br>
Mount the google drive after enter the Colab environment<br>
![image](https://user-images.githubusercontent.com/79595031/164977802-7c5186cb-897a-4f8e-a449-cf74ce587447.png)

Verify the data Source is usable on the Google Drive.<br>
Change the path according to your google drive setting. <br>
The dataset need to be downloaded and mounted from google drive first <br>
After mounting, the dataset file should be something like: <br> "/content/drive/(the path of dataset on your google drive path)" <br>

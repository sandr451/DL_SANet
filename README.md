## Paper:

+ Original_paper: [_Cao, X., Wang, Z., Zhao, Y., & Su, F. (2018). Scale Aggregation Network for Accurate and Efficient Crowd Counting. *The European Conference on Computer Vision (ECCV)*, 1–17_](http://openaccess.thecvf.com/content_ECCV_2018/html/Xinkun_Cao_Scale_Aggregation_Network_ECCV_2018_paper.html).

How To Test the Model:

#Create a new conda environment using the GUI or the following command in conda cmd(use python version >3.6 & <3.7, i.e python 3.6.13):

conda create -n new_testing_environment python=3.6.13
conda activate new_testing_environment

#Clone the Git repository using:

git clone https://github.com/KayBee8268/DL_SANet


#Go inside the DL_SANet directory:

cd DL_SANet


#install the requirements using the following 2 commands:

conda install cudatoolkit=10.0 cudnn=7.6.5
pip install -r requirements.txt


#Now, all the dependencies for testing are installed. Open JupyterNoteBook in this environment and run all the cells in test.ipynb 

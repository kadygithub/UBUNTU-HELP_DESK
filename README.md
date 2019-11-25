# UBUNTU-HELP_DESK
ubuntu coomandline
print(tf.__version__)
print(tf.__version__): 2.0.0
pip list | grep tensorflow : show the version of Tensorflow installed


---------------  conda environment ------------------------
1- conda create -n tensorflow_env tensorflow : if it has activated before no need

conda info --envs
conda activate anaconda3/envs/tensorflow_env
conda deactivate
anaconda-navigator 
--------------------------------------------   opencv
install open cv  :  y

check version in python : 
>>> import cv2 as cv
>>> print(cv.__version__)
3.4.2

-------------------------- another version of tensorflow in conda
conda create -n tensorflow_env2 tensorflow==1.14
conda activate tensorflow_env2

---------------------------  tensorflow gpu 
conda create --name tf__gpu tensorflow-gpu




------------------------  implementing InfoGAN ----------------------

https://github.com/fangihsiao/InfoGAN-Tensorflow
1- go to directory you want to have the code in jupiter terminal :
git clone https://github.com/fangihsiao/InfoGAN-Tensorflow


-----------------------------  EHR ------------------
https://github.com/mp2893/medgan


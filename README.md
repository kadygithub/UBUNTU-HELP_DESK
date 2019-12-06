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

---------------------------  tensorflow gpu  tensorflow version 2
conda create --name tf__gpu tensorflow-gpu

-------------------------  tensorflow version 1, cudaa 10.2 cuDNN: 7.6.5
conda activate tf-v1__gpu



---------------------------------  Gpu version of tensorflow
conda activate tf__gpu   #version tensorflow 2.0.0

anaconda-navigator 


---------------------  panda 
conda install -c anaconda pandas


------------------------  implementing InfoGAN ----------------------

https://github.com/fangihsiao/InfoGAN-Tensorflow
1- go to directory you want to have the code in jupiter terminal :
git clone https://github.com/fangihsiao/InfoGAN-Tensorflow

----------------------- IMPLEMENT SIMPLE GAN  PYTHORCH OR TENSORFLOW
https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f


-----------------------------  EHR ------------------
https://github.com/mp2893/medgan


------------------------ cuda and cuDNN --------------------
Check the CUDA version:

cat /usr/local/cuda/version.txt
and cuDNN version:

grep CUDNN_MAJOR -A 2 /usr/local/cuda/include/cudnn.h

installation process: 

----------------- docker image : tensorflow+cuda+cudnn
https://stackoverflow.com/questions/50622525/which-tensorflow-and-cuda-version-combinations-are-compatible

---------------- aman's project --------------------
~/Documents/3fields-papers/aman-GAN_PROJECT/staining_aman$ python pix2pix.py --mode train  --input_dir ./patch_datasets/staining_and_destaining_train_patch_dataset --output_dir ./trained_models/staining_patches_trained_model



---------------------pix2pix ----------------------
https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/pix2pix.ipynb



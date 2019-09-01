# CNN_Backup

Backup of GIM code for thesis

The Sentinel_2_CNN 1D and 2D files contain the code for running the Convolutional Neural Networks. Note that the ee_datasets.py needs to be saved down to the same Jupyter environment. 

This code was run on a Google Compute Virtual Instance running on a Nvidia GPU.

Main reference gits can be found in cloned repositories - major thanks to Skydipper and Jiaxuan for a major platform to build upon

https://github.com/JiaxuanYou/crop_yield_prediction


https://github.com/holden590/cnn-models

step 1 
  sudo find . -name *.ipynb
step 2 - set the working directory 
  cd ./home/holden590/Skydipper/Notebooks/
step 3 - launch Jupyter notepad
  jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser &

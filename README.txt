#One possible solution to prepare the environment is to install conda:
https://docs.conda.io/en/latest/miniconda.html
#After the installation you can create the environment with the following command:
conda create --name torch-39 python=3.9 numpy  pytorch::pytorch torchvision torchaudio -c pytorch
#Activate the environment:
conda activate torch-39
# Intall the remaining libraries:
conda install -c conda-forge matplotlib
conda install scikit-learn pandas
conda install -c conda-forge notebook jupyterlab nb_conda_kernels jupyter_contrib_nbextensions
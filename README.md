Simplified version:

1. Install Miniconda: Download and install Miniconda from https://docs.conda.io/en/latest/miniconda.html.

2. Create environment: Open a terminal and run conda create --name torch-39 python=3.9 numpy pytorch::pytorch torchvision torchaudio -c pytorch.

3. Activate environment: Run conda activate torch-39.

4. Install libraries: Run conda install -c conda-forge matplotlib scikit-learn pandas notebook jupyterlab nb_conda_kernels jupyter_contrib_nbextensions.

5. Start Jupyter: Run jupyter notebook or jupyter lab.

6. Choose environment: Select the "torch-39" kernel in Jupyter to use the created environment.

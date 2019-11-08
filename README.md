# TensorFlowInstallation

conda create -n MNISTworkshop python=3.7
	creates the environment
	
conda activate MNISTworkshop

pip install ipykernel
	kernel for the environment

python -m ipykernel install --user --name MNISTworkshop --display-name "MNISTworkshop"
	installs the kernel

conda install tensorflow
conda install tensorflow-gpu
	installs everything needed to install tensorflow/tensorflow-gpu

conda install jupyter

pip install keras
	neural network api
	
jupyter notebook

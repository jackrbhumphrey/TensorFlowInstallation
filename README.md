# TensorFlowInstallationWindows10


Install Anaconda
https://www.anaconda.com/distribution/#download-section

Install the latest version of Python supposed by Tensorflow (Currently, this is Python 3.7)
https://www.python.org/downloads/

Open the "Anaconda Prompt(Anaconda3)" executable

Installing TensorFlow: 

 	- These seven steps are used to install TensorFlow
		This works for all machines, but is slower than TensorFlow-GPU

	conda create -n MNISTworkshop python=3.7
	conda activate MNISTworkshop
	pip install ipykernel
	python -m ipykernel install --user --name MNISTworkshop --display-name "MNISTworkshop"
	conda install tensorflow
	conda install jupyter
	pip install keras



	 - These seven steps are used to install TensorFlow-GPU
		THIS IS FOR SYSTEMS OPERATING WITH A DEDICATED GPU

	conda create -n MNISTworkshop python=3.7
	conda activate MNISTworkshop
	pip install ipykernel
	python -m ipykernel install --user --name MNISTworkshop --display-name "MNISTworkshop"
	conda install tensorflow-gpu
	conda install jupyter
	pip install keras


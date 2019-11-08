# TensorFlowInstallationWindows10


Install Anaconda.  As of 11/8/19, I would recommend the Python3.7 version.
https://www.anaconda.com/distribution/#download-section

Open the "Anaconda Prompt(Anaconda3)" executable

Installing TensorFlow: 

 	- These seven steps are used to install TensorFlow
		This works for all machines, but is slower than TensorFlow-GPU

	//////////////////////////////////////////////////////
	
	conda create -n MNISTworkshop python=3.7
	
	conda activate MNISTworkshop
	
	pip install ipykernel
	
	python -m ipykernel install --user --name MNISTworkshop --display-name "MNISTworkshop"
	
	conda install tensorflow
	
	conda install jupyter
	
	pip install keras

	//////////////////////////////////////////////////////

	 - These seven steps are used to install TensorFlow-GPU
		THIS IS FOR SYSTEMS OPERATING WITH A DEDICATED GPU
         
	//////////////////////////////////////////////////////

	conda create -n MNISTworkshop python=3.7
	
	conda activate MNISTworkshop
	
	pip install ipykernel
	
	python -m ipykernel install --user --name MNISTworkshop --display-name "MNISTworkshop"
	
	conda install tensorflow-gpu
	
	conda install jupyter
	
	pip install keras
	
	//////////////////////////////////////////////////////

Using this video, you can see how to implement 

# Ml-project
image classification using deep learning
This repository has a files for this assignment
There is MLP.py, CCN.py, 
there is Makefile which is structure in this format

This algorithms uses the the CIFAR10 dataset

run:
	python MLP.py  # complile the network

setup:
	python3 -m venv venv              # create virtual environment 
	source ./venv/bin/activate        # activating the virtual environment
	pip install PACKAGE_NAME          # adding packages for python
	pip install -r requirements.txt   # installing requirement for the projects

build:
	python setup.py bdist_wheel

clean:                            # cleanup project when rebuilding project            
	rm -rf venv

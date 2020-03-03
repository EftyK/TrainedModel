# TrainedModel
This repository containes a ready-to-use tensorflow model, for the purpose of identifying Platanus hispanica and Celtis australis trees in the streets of Barcelona, Spain.

## Contents
The Jupyter notebook (IdentifyTreeSpecies.ipynb) loads a trained tensorflow model visualizes the results.

Apart from the Jupyter notebook, this repository provides the aforementioned model, the corresponding tree species label map and some images for testing the model. 

## Prerequisites
To run IdentifyTreeSpecies.ipynb, you must have the following prerequisites installed on your system:
* Python > 3.6.0
* jupyter-console 6.1.0 
* tensorflow-cpu 2.1.0 (use pip install)
* tensorflow object_detection API (see instructions [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md) )

...as well as the following libraries (can also be installed through pip):
* numpy 1.17.2
* pathlib2 2.3.5
* ipython 7.8.0

The instructions above should end in acquiring locally the tree-structured project directories of Tensorflow. \
Example: \
-tensorflow \
&nbsp;&nbsp;&nbsp;&nbsp; -models \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;-research \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; -object_detection \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; ... \
&nbsp;&nbsp;&nbsp;&nbsp; ...

## How to use this project
Download the folder and copy it under object_detection. Now your file structure should be:
-tensorflow \
&nbsp;&nbsp;&nbsp;&nbsp; -models \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;-research \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; -object_detection \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; -TrainedModel \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; ... \
&nbsp;&nbsp;&nbsp;&nbsp; ...


Open IdentifyTreeSpecies.ipynb and run the cells consecutively. When you reach the last executable cell, you should get an output like this:

![Example output](example.png)
*Fig. 1 - Example output*

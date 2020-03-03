# TrainedModel
This repository containes a ready-to-use tensorflow model, which is aimed to identify Platanus hispanica and Celtis australis trees in the streets of Barcelona, Spain.

## Files' description
The Jupyter notebook (IdentifyTreeSpecies.ipynb) will load a trained tensorflow model that also handles the visualization of the results.

Apart from the Jupyter notebook, this repository provides the aforementioned model, the corresponding tree species label map and some images for testing the model. 

## Prerequisites
For this setup execute successfully, there are certain prerequisites that need to be already part of your system:
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

## How to identify tree species?
Download the folder and copy it under object_detection.

Open IdentifyTreeSpecies.ipynb and run the cells consecutively. When you reach the last executable cell, you should get an output this:

![Example output](example.png)
*Fig. 1 - Example output*

# TrainedModel
This repository contains a ready-to-use tensorflow model for the purpose of identifying Platanus hispanica and Celtis australis trees in the streets of Barcelona, Spain.

## Contents
The Jupyter notebook (IdentifyTreeSpecies.ipynb) loads the trained tensorflow model and visualizes the results.

Apart from the Jupyter notebook, this repository provides the aforementioned model, the corresponding tree species label map and some images for testing the model. 

## Prerequisites
To run IdentifyTreeSpecies.ipynb, you will need a number of prerequisites. Follow these steps to install them on your system:

1. Install Python > 3.6.10

2. The following 4 commands will install almost all packages that you will need:
```Bash
pip install tensorflow-cpu
pip install jupyter
pip install lxml
pip install contextlib2
```

3. Download or git clone [tensorflow/models](https://github.com/tensorflow/models) repository.

This should result in acquiring locally the tree-structured project directories of Tensorflow. \
Example: \
-models \
&nbsp;&nbsp;&nbsp;&nbsp;-research \
&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; -object_detection \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;... \
&nbsp;&nbsp;&nbsp;&nbsp; ...

4. Navigate to models/research directory and run
```Bash
pip install .
```

## How to use this project
1. Download or git clone the repository and copy it under object_detection. Now your file structure should be: \
-models \
&nbsp;&nbsp;&nbsp;&nbsp;-research \
&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; -object_detection \
&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; -TrainedModel \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; ... \
&nbsp;&nbsp;&nbsp;&nbsp; ...


2. Open IdentifyTreeSpecies.ipynb and run the cells consecutively. When you reach the last executable cell, you should get an output like this:

![Example output](example.png)
*Fig. 1 - Example output*

# TrainedModel
This repository containes a ready-to-use tensorflow model, for the purpose of identifying Platanus hispanica and Celtis australis trees in the streets of Barcelona, Spain.

## Contents
The Jupyter notebook (IdentifyTreeSpecies.ipynb) loads a trained tensorflow model visualizes the results.

Apart from the Jupyter notebook, this repository provides the aforementioned model, the corresponding tree species label map and some images for testing the model. 

## Prerequisites
1. Python > 3.6.10

2. The following 4 commands will install almost all packages that you will need:
```Bash
pip install tensorflow-cpu
pip install jupyter
pip install lxml
pip install contextlib2
```

3. Download or git clone [this](https://github.com/tensorflow/models) repository.

The instructions above should end in acquiring locally the tree-structured project directories of Tensorflow. \
Example: \
-models \
&nbsp;&nbsp;&nbsp;&nbsp;-research \
&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp; -object_detection \
&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;... \
&nbsp;&nbsp;&nbsp;&nbsp; ...

4. Navigate in models/research directory and run
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

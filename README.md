# Machine Learning Engineer Nanodegree
# Deep Learning
## Project: Image Classification

### Install

This project requires **Python 3.5** and Conda package manager

Mac & Linux:  
```bash
conda create -n tensorflow python=3.5
source activate tensorflow
conda install pandas matplotlib jupyter notebook scipy scikit-learn
conda install -c conda-forge tqdm
pip install tensorflow
```

Windows:  
```bash
conda create -n tensorflow python=3.5
activate tensorflow
conda install pandas matplotlib jupyter notebook scipy scikit-learn
conda install -c conda-forge tqdm
pip install tensorflow
```

### Code

A notebook is provided as `image_classification.ipynb`. There is also a helper.py file with functions that help preprocess and display the data. Also, unit tests are provided in the problem_unittest.py file. 

### Run

In a terminal or command window, navigate to the top-level project directory `image_classification/` (that contains this README) and run the following command:

```bash
jupyter notebook image_classification.ipynb
```

or if tensorflow is not activated run these commands:

```bash
activate tensorflow
jupyter notebook image_classification.ipynb
```

This will open the Jupyter Notebook software and notebook file in your browser.


### Data

While no data is directly provided with the project, the notebook will download and use the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html)


Accessing the Notebooks
-----------------------

On linux, go to: http://127.0.0.1:8888

On mac, find the virtual machine's IP using:

    docker-machine ip default

Then go to: http://IP:8888 (likely http://192.168.99.100:8888)

Troubleshooting
-----------------------

If the notebook displays the error "Kernel not found," try running the commands:

```bash
activate tensorflow
jupyter notebook image_classification.ipynb
```
# Tensorflow_TFRecords_Estimator_Pipeline
A pipeline/template for
- Converting dataset in TFRecords
- Training and evaluating multi-calss image classifier using custom tensorflow estimator

## Requirements
Tensorflow >= 1.4.0

### Setup Environment
```sh
# Virtual environment (optional)
sudo apt install -y virtualenv

# Tensorflow (optional)
sudo apt-get install python3-pip python3-dev python-virtualenv # for Python 3.n
virtualenv --system-site-packages -p python3 tensorflow170_py35_gpu # for Python 3.n with GPU
source tensorflow170_py35_gpu/bin/activate
easy_install -U pip
pip3 install --upgrade tensorflow-gpu # for Python 3.n and GPU
```

## Dataset
Download knifey-spoony dataset
```sh
cd scripts
./download_dataset_knifey_spoony.sh
```

## Train and evaluate
```sh
./run.sh
```

## Acknowledgment
https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/18_TFRecords_Dataset_API.ipynb
https://github.com/MrGemy95/Tensorflow-Project-Template

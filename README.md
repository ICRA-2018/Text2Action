# Text2Action
<a href="#roslab-run"><img src="https://img.shields.io/badge/ROSLab-run-brightgreen.svg"></a>

# ROSLab Run

## Prerequisites:
* [Docker](https://www.docker.com/)
* Tested on Ubuntu Linux 16.04, Docker version 18.06.1-ce.

## 1. Clone the repository and build ROSLab image:
```
git clone https://github.com/ICRA-2018/Text2Action.git
cd Text2Action
./roslab_build
```
## 2. Launch ROSLab image:
```
./roslab_run
```
## 3. Open JupyterLab in your browser:
[http://localhost:8888/lab/tree/README.ipynb](http://localhost:8888/lab/tree/README.ipynb)

## 4. Run in JupyterLab:

Open a test notebook and run all the cells.

* [test_GAN notebook](exec/test_GAN.ipynb)
* [train_GAN notebook](exec/train_GAN.ipynb)
* [train_seq2seq notebook](exec/train_seq2seq.ipynb)

## CoType
CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases

## Publication

* Xiang Ren\*, Zeqiu Wu, Wenqi He, Meng Qu, Clare R. Voss, Heng Ji, Tarek F. Abdelzaher, Jiawei Han, "**[CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases](https://arxiv.org/pdf/1610.08763v1.pdf)**”, arXiv:1610.08763.

## Requirements

We will take Ubuntu for example.

* python 2.7
```
$ sudo apt-get install python
$ pip install pexpect
```

* [stanford coreNLP 3.5.2](http://stanfordnlp.github.io/CoreNLP/) and its [python wrapper](https://github.com/dasmith/stanford-corenlp-python). Please put the library in folder DataProcessor/.

* [eigen 3.2.5](eigen.tuxfamily.org/). Please put the library in folder Model/.

* cd /Model/reType and "make"

## Dataset
Three datasets used in the paper could be downloaded here:
   * [BioInfer](https://drive.google.com/drive/folders/0B--ZKWD8ahE4RmFBTjR6aUJjTkU?usp=sharing)
   * [NYT](https://drive.google.com/drive/folders/0B--ZKWD8ahE4UktManVsY1REOUk?usp=sharing)
   * [KBP](https://drive.google.com/drive/folders/0B--ZKWD8ahE4RjFLUkVQTm93WVU?usp=sharing)

Please put the data files in corresponding subdirectories in Data/.

## Default Run
Run CoType for the task of Reduce Label Noise on the BioInfer dataset

```
$ ./run.sh  
```

## Parameters - run.sh
Dataset to run on.
```
Data="BioInfer"
```

# BXD project

The BXD project aims at revealing and exploring the complex relationship between mice genes, phenotypes, protein expression in tissues and more. The main goal of this repository is to provide a tutorial on the data and different machine learning approaches used for investigating the mice data. It is coded in python with jupyter notebooks. Each notebook focus on a particular aspect of the data or a particular ML method.

## List of notebooks

Here is the list of notebooks with a short description.

* `data_exploration.ipynb`: introduction to the dataset with a decription of the different files and what they contain.
* `random_forest-phenotypes-genotypes.ipynb`: A simple implementation of Random Forest to find complex combination of genes that could influence phenotypes.

## How to run the tutorials

There are several possible ways to run the notebooks.
* clone the repository on a local machine with python and jupyter installed, along with several data mining and machine learning modules. The simplest is to install Anaconda. 
* The nobebooks can be run online for example using [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/graphnex/BXDmice/HEAD). Everything will run online without the need to install anything on the personal machine. However it may be slower and the user can experience disconnections during long period of inactivity.

## BXD data

The dataset for the experiments is open and stored on an server from EPFL. It is a s3 storage at `'endpoint_url':'https://os.unil.cloud.switch.ch'` that can be accessed using the url `'s3://lts2-graphnex/BXDmice/`. See the notebooks for access examples.

## Dataset description

The dataset contains genomic data, protein expression in different body tissues of the mouse as well as the phenotype of mice over more that 5000 different experiments. The experiments cover a wide range of tests such as obesity related, insulin or expression of a variety of health markers in the mouse. 
# DATA2060_FinalProject

## Overview

This project is about CART - Classification and Regression Tree for classification. We used the heart disease dataset on kaggle

(https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

The goal is to implement CART using only numpy, and the result should match Scikit-learn's result. You can find our implementation in the src file.

From the result we can say that we achieved success because we got the exact same result and tree structure as Scikit-learn's result and tree structure.

More details about the implementation is in the pdf.

## Prerequisites

Dependencies are listed in the yml file. 

Python version 3.12.7, all other package version are in the dependencies.yml file

Run these two commands in the terminal:

`conda env create -n data2060 -f dependencies.yml`

`conda activate data2060`

For macOS, use `brew install graphviz` to graph your own tree. 

For Ubuntu/Debian, use `sudo apt-get update` followed by `sudo apt-get install graphviz`

You can use `dot -V` to verify the installation.

Our result is stored in the graph folder

## Author, listed alphabetically by last name

Yixun Kang (yixun_kang@brown.edu), David Ning (zhenglin_ning@brown.edu), Liang Zhang (liang_zhang1@brown.edu)

## License

This project is licensed under the MIT license.
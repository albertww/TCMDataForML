# TCMDataForML

## Basic
Provide the traditional Chinese medicine data used for machine learning

Currently the raw information comes from https://lib-nt2.hkbu.edu.hk/database/cmed/cmfid/index.asp

The csv file is generated by the python file with the command "python3 writeDataSet.py".

The information in the column "composition" and "label" in the csv file could be used to train a Text Categorizer Model,
then the model could be used to predict the "label" of any "composition".

To have more idea how to do the training, here is an example https://www.kaggle.com/matleonard/text-classification

## TODO
1. Enrich the python file and the csv file.

2. Have the torken for the traditional Chinese medicine data text.

## Last
Enjoy!  Please free to contact me by zuguoxiang@foxmail.com



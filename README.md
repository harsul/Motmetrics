# Motmetrics
How to evaluate motmetrics

The py-motmetrics library provides a Python implementation of metrics for multiple object trackers (MOT) benchmark described in [Py-Motmetrics](https://github.com/cheind/py-motmetrics)

## Steps to do:

1. Download this repository

## RUN COMMAND

*python -m motmetrics.apps.eval_motchallenge (yourPathtoExampleFolderGroundTruth) (yourPathToExampleFolder)*


# Do with your own dataset results

* Download data sets from [MOT Chellenge](https://motchallenge.net/)

* Run your MOT framework (I ran the [DeepSORT](https://github.com/nwojke/deep_sort) on MOT16-03)

* Save tracking results as **file_name.txt**

* Make folder name as same of the **results** file that has got tracking results 

* Copy **gt** from MOT folder inside results folder and make sure that you have **gt.txt** inside it  

* Copy the **results.txt** inside the same folder 

* Open Python and run the command






# Motmetrics
How to evaluate motmetrics

The py-motmetrics library provides a Python implementation of metrics for multiple object trackers (MOT) benchmark described in [Py-Motmetrics](https://github.com/cheind/py-motmetrics)

## Steps to do:

* Download data sets from [MOT Chellenge](https://motchallenge.net/)

* Run your MOT framework (I ran the [DeepSORT](https://github.com/nwojke/deep_sort) on MOT16-03)

* Save tracking results as **MOT16-XX.txt**

* Make folder name as same of the **MOT16-XX** file that has got tracking groundtruth from dataset 

* Copy **gt** from MOT folder inside results folder and make sure that you have **gt.txt** inside it  

* Open Python and run the command


## RUN COMMAND

*python -m motmetrics.apps.eval_motchallenge (yourPathtoExampleFolderGroundTruth) (yourPathToResultsFolder)*

![image](https://github.com/harsul/Motmetrics/blob/main/motchallenge-16.PNG)





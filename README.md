# Fast.ai Time Series Learning Challange: S&P500 

Welcome to the second fast.ai learning challange. Unlike traditional Kaggle competitions, 
the main goal of a learning competition is learn and share our knowledge within the fastai community by fostering collaboration.

Close in spirit to the [first challange about earthquakes](https://forums.fast.ai/t/welcome-to-our-first-time-series-learning-competition-earthquakes/30951), 
we believe that by focusing our work on the same dataset, we will be able to learn and share our knowledge with the DL/ML community in a very practical way.   

## Objective: 

The objective of the competition is to learn as much as possible about predicting time series data and share that knowledge with the rest. 
The performance (in this case val accuracy) will obviously help us gauge the value of different proposed approaches, but it’s not the main driver for this competition.

## Challenge:

* Predict the S&P 500 closing price of the next day.
* Bonus: predict next 1,3,5 days
* Anyone can join

## Data: 
* 50 Years of [S&P500 data](https://github.com/marvin-hansen/SP-contest/tree/master/Data) 
* Standard OHLCV format:  Open, High, Low, Close Prices and Volume data 
* Quality data: No missing 

## Getting started: 
Choice 1: [Download the 50 Year dataset](https://github.com/marvin-hansen/SP-contest/tree/master/Data)  

Choice 2: Get the [sample data loader notebook](https://github.com/marvin-hansen/SP-contest/blob/master/SP500.ipynb)
   * The sample data loader contains only scripts to download and split the data into train and test without any fearture engineering. By default, the last 30 days are used as vaildation dataset. Set valid to zero in case no validation dataset is required.  

Choice 3: Get the [sample data processor notebook](https://github.com/marvin-hansen/SP-contest/blob/master/SAMPLE_Data_Proc_V_0_7.ipynb) 
  * The sample data processor contains a data loader, several sample feature generators, and other tools for feature engineering. 

Choice 3: Take a loot at the Rossmann [data processing](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/rossman_data_clean.ipynb) and the [tabular model](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/lesson6-rossmann.ipynb)


## Learning competition rules:

1. We will openly share ideas, provide feedback to others, and will upload our notebooks to a shared time series repository created for this learning competition [Repo](https://github.com/marvin-hansen/SP-contest/tree/master/).

2. Deadline: In Seven weeks (May 21, 2019), although we can extend it if you are interested.

3. Ideas, feedback, performance results for this competition should be shared in the corresponding forum thread.

4. There won’t be any test set or formal submission process. Just create a notebook gist it, write a post in this thread, 
and share your notebook/ gist with your results (if you have any idea how to do this more efficiently just let us know).

5. You can use any technical approaches to this problem (deep learning or not, fastai or not).

**Award:**  Learning, contribution, recognition and ... (any more ideas?)  

## Ideas and areas of exploration:
* CoordConv ([Paper](https://arxiv.org/pdf/1807.03247.pdf)) ([Repo](https://github.com/mkocabas/CoordConv-pytorch)) ([Ueber](https://eng.uber.com/coordconv/))
* [Pytorch + pyro](https://forums.fast.ai/t/time-series-sequential-data-study-group/29686/182)
*  [Deep Neural Network Ensembles for Time Series Classification: SOTA](https://forums.fast.ai/t/time-series-sequential-data-study-group/29686/168)
* [Bayesian Convolutional Neural Network](https://github.com/kumar-shridhar/Master-Thesis-BayesianCNN)
* [Hinton’s Capsule Networks](https://medium.com/ai%C2%B3-theory-practice-business/understanding-hintons-capsule-networks-part-i-intuition-b4b559d1159b)
* Time series feature engineering with **[tsfresh](https://github.com/blue-yonder/tsfresh)**
* [Transfer learning](https://forums.fast.ai/t/time-series-sequential-data-study-group/29686/175)
* And more, please add in the comments 



We look forward to having you participate in this competition. Thanks!


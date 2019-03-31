# Fast.ai Time Series Learning Competition: S&P500 

Welcome to the second fast.ai learning challange. Unlike traditional Kaggle competitions, 
the main goal of a learning competition is learn and share our knowledge within the fastai community by fostering collaboration.

Close in spirit to the [first one about earthquakes](https://forums.fast.ai/t/welcome-to-our-first-time-series-learning-competition-earthquakes/30951), 
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
   * The sample data loader only contains a script to download and split the data into train and test without any engineering.

Choice 3: Get the [sample data processor notebook](https://github.com/marvin-hansen/SP-contest/blob/master/SAMPLE_Data_Proc_V_0_7.ipynb) 
  * The sample data processor contains a download script among other things so all you need to to do is to open it in Colab and run it. 

Choice 3: Take a loot at the Rossmann [data processing](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/rossman_data_clean.ipynb) and the [tabular model](https://nbviewer.jupyter.org/github/fastai/course-v3/blob/master/nbs/dl1/lesson6-rossmann.ipynb)


## Learning competition rules:

1. We will openly share ideas, provide feedback to others, and will upload our notebooks to a shared time series repository created for this learning competition [Repo](https://github.com/marvin-hansen/SP-contest/tree/master/).

2. Deadline: In Seven weeks (May 21, 2019), although we can extend it if you are interested.

3. Ideas, feedback, performance results for this competition should be shared in the corresponding forum thread.

4. There won’t be any test set or formal submission process. Just create a notebook gist it, write a post in this thread, 
and share your notebook/ gist with your results (if you have any idea how to do this more efficiently just let us know).

5. You can use any technical approaches to this problem (deep learning or not, fastai or not).

**Award:**  Learning, contribution, recognition and ... (any more ideas?)  


We look forward to having you participate in this competition. Thanks!


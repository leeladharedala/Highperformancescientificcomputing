# Comparing Execution Time, Speedup, and Efficiency of Serial and Parallel Machine Learning Model Training for House Price Prediction and Credit Card Fraud Detection

The purpose of this study is to determine how parallelization affects the effectiveness of machine learning model training for predicting home prices and detection of fraud for credit card.

The time-consuming nature of machine learning model training on huge datasets, notably in the context of housing price prediction, is the issue this work attempts to solve. The objective is to create and apply a parallel computing strategy to quicken training and increase model effectiveness.

It can take a long time to train machine learning models on large datasets, and it might not be possible to do so on a single processor. A solution is provided by parallel computing, which divides the data into smaller chunks and processes them concurrently on numerous processors or nodes, shortening the training period.

We can see that when we increase the number of processors, the speedup likewise increases since the speedup is the ratio of the serial time to the parallel time. However, it is clear that efficiency declines as the number of processors rises. A decline in efficiency shows that the additional processors are not being used effectively. Efficiency is the ratio of speedup to the number of processors. These findings indicate that employing two processors would be the ideal arrangement for the first dataset

We can observe from the second dataset that, regardless of the processor arrangement, the parallel time is not much faster than the serial time. The dataset's characteristics or the method in use may be to blame for this. We can observe that the speedup is almost 1 for all setups, which shows that parallel processing does not significantly reduce training time. The efficiency is likewise fairly poor, showing inefficient use of the extra processors.

Install python, neccessary libraries and run the ipynb file for results

 

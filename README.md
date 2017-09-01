# Spark-SQL

Proof of concept - Spark SQL

Project Description : Stock Market Analysis – NSE India

Dataset Resource : https://www.kaggle.com/ramamet4/nse-company-stocks

Special operation :

              a. Compute the average closing price per day per company
              
              b. List the companies with highest closing prices
              
              c. List the number of big price rises and falls
              
              d. Compute hourly average closing price for each company
              
              e. Find the greatest Volume
              
              f. Save and read back original dataframe as parquet file
                            
              
Goal : Doing the various operations on the stock market yearly data

The project done on Cloudera Quickstart VM 5.10 CDH.

Note : Original data was divided into 5 csv files and total it was 1.9 GB data.  While sorting/shuffling it was running out of memory issue.  So I further checked the operations on only 1 file out of 5.  However it also failed with same issue.  Hence took part of 1 st input file and performed the operations on it.

Intention is to run the commands on the small set of data SUCCESSFULLY.

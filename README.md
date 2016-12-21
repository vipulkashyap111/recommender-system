# Recommender System  

The code in this repo is based on the following paper: [Recommender System] (https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)

The recommendation is generated using the technique of collaborative filtering. User and Product bias is removed before creating the model for more accurate recommendation. The code is written in IPython Notebook and makes use of Apache Spark Framework and pyspark's mllib library.

## Usage  
1. Follow the instructions in [Tutorial-Spark] (https://github.com/vipulkashyap111/recommender-system/blob/master/Tutorial-Spark.pdf) file in the repo to setup Spark and IPython Notebook on your machine.
2. Update the code to modify the path to your dataset. Please note that you need to have 2 separate datasets: training dataset and test dataset. For better performance create multiple pairs of the data split and run the code on all the pairs.
3. Run the IPython notebook file
`$IPYTHON_OPTS="notebook"$SPARK_HOME/bin/pyspark`

# pig-twitter-analysis
This example used a Pig script to analyze trending words twitter

Twitter_Test_Samp200 is a sample of twitter data, related to elections in 2012 used for the twitter trending example. There are only 2 dates here, Sun Sep 30 2012 and Mon Oct 08 2012, and about 200 rows. Change the Pig script to use one of these dates if you want to run it. 

index_data.csv is a collection of Yelp reviews.

#Instructions for Twitter analysis
1. Copy files from local system to HDFS:
   fs -copyFromLocal /home/cloudera/Twitter_Test.json /user/cloudera/pigin/
2. 


#Instructions for Yelp analysis
1. Check out the header row of index_data.csv to see the categories in the file.
2. Copy the dataset into HDFS using the command hdfs dfs -copyFromLocal *local_File* *hdfs_directory*
3. Start the grunt terminal to run pig commands with:
   pig -x mapreduce
 

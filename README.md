# Building a Big Data Ecosystem in the Cloud (Digital Innovation One Project)
Project was taught by instructor Cassiano Peres (https://github.com/cassianobrexbit/DIO-LiveCoding-AWS-BigData)

I changed:
1) The command to run the mrjob from explicitly defined location
python dio-live-wordcount-test.py -r emr s3://{your_s3_bucket_name}/data/sherlock.txt --conf-path mrjob.conf --output-dir=s3://{your_s3_bucket_name}/output/logs1 --cloud-tmp-dir=s3://{your_s3_bucket_name}/temp/
2) Removed ssh connection from .conf file

Objectives:
* Explore Amazon Web Service (AWS)
* Create a cluster from Mrjob
* Create a bucket in S3
* Get AWS ID and secret key to configure Mrjob 
* Perform data processing
* Run a Hadoop MapReduce Job for counting words from a book
* Monitor cluster creation and termination from EMR

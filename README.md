# SettingUpSparkCluster
Steps for setting up a Spark Cluster on Ubuntu

1. Check if Java is installed == java -version
2. If not, install it as follows: 
sudo apt update, sudo apt-get install openjdk-8-jdk, java -version 

3. Install scala
sudo apt-get install scala, scala -version

4. Download targz file from Apache Spark's download link : https://spark.apache.org/downloads.html

5. Go to the directory of installation and extract the file :
tar xvf spark-....tgz

6. Move it to the local filesystem:
sudo su - , cd /home/yourusername/Downloads/, mv spark-.... /usr/local/spark, exit

7. Configure spark
export PATH=$PATH:/usr/local/spark/bin

8. Run spark-shell

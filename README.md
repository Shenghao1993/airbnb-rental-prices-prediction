# spark-examples
A series of learning examples of Apache Spark. Both Scala and PySpark examples are included.

# Set up Spark notebook
1. Make sure JAVA_HOME and SPARK_HOME are in the bash script.
export SPARK_HOME=~/spark/spark-2.2.1-bin-hadoop2.7
export PATH=$PATH:$SPARK_HOME/bin
2. Install a Jupyter kernal to integrate it with Apache Saprk. One option is Apache Toree, available at https://toree.apache.org/download/. The kernal can be installed by running
```
pip install --upgrade toree
```
3. Configure Apache Toree with Jupyter Notebook by running
```
jupyter toree install --spark_home ~spark-2.2/spark-2.2.1-bin-hadoop2.7/ --interpreters=Scala,PySpark,SQL --user
```
4. Reference: https://medium.com/@singhpraveen2010/install-apache-spark-and-configure-with-jupyter-notebook-in-10-minutes-ae120ebca597
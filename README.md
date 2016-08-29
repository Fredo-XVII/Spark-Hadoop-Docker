# Spark-Hadoop-Docker
Trying to run spark and hadoop on a docker container


# Notes:
> Make sure to use Dockers Kimatic if you can't find the container.  Kilmatic will tell you where the ports are for the Hadoop nodes and the ambari job tracking page when the Hadoop cluster is up and running.  It will give you the file path to the 50070 node, currently it is http://192.168.99.100:32770/dfshealth.html#tab-overview , so the docker created the 32770 for the 50070 node.

- installing Anaconda to manage package dependencies on the master and slave nodes :
  - https://www.continuum.io/blog/developer-blog/using-anaconda-pyspark-distributed-language-processing-hadoop-cluster

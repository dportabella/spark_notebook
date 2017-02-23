# Spark notebook

Some Spark Scala examples on notebook/jupyter:

- word count using countByValue
- word count using map-reduce
- compute pi
- Spark SQL
- ML decision tree


# Requirements
- install docker
- install git


# Run
```
$ git clone https://github.com/dportabella/spark_notebook.git
$ cd spark_notebook
$ docker run -p 9001:9001 -v $PWD:/tmp/notebook -e NOTEBOOKS_DIR=/tmp/notebook andypetrella/spark-notebook:0.7.0-scala-2.11.8-spark-2.1.0-hadoop-2.7.3
```

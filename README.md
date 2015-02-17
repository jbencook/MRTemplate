# Simple MapReduce Template: Word Count

## To compile:

    mvn clean install

## To run:

    export HADOOP_CLASSPATH=target/MRTemplate-1.0.jar
    hadoop WordCount <input path> <output path>
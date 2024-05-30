# Spark SQL and DataFrames

- install Spark https://www.apache.org/dyn/closer.lua/spark/
- put into path for shell (see below)
- Install Brew for Mac
- Install JDK https://www.oracle.com/java/technologies/downloads/
- brew install java
- install latest python
- install pip
- pip install numpy
- pip install pyspark
-   export SPARK_HOME="/Users/{REPLACE_USERID}/spark"
    export PATH=$SPARK_HOME/bin:$PATH
    export PYSPARK_DRIVER_PYTHON=jupyter
    export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
    alias python=/Library/Frameworks/Python.framework/Versions/3.12/bin/python3
    export JAVA_HOME= /opt/homebrew/opt/openjdk@21/libexec/openjdk.jdk/Contents/Home

#To Run
pyspark

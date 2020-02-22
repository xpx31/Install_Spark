# Install Spark

Install Spark for Python

## Installation Guide

### Install Spark
Spark download link:  
[https://spark.apache.org/downloads.html](https://spark.apache.org/downloads.html)

or  

```bat
  pip3 install pyspark
```

### Save Spark to home directory
Rename and save Spark folder to home directory

```bat
  your_home_directory/spark
```


### Add Spark to PATH variable
Go to home directory in terminal

```bat
  cd your_home_directory
```

Change / add .bash_profile file, and add the path variables in the file

```bat
  export SPARK_HOME="your_home_directory/spark"
  export PATH="$SPARK_HOME/bin:$PATH"
```

Save and exit the terminal

### Test PySpark

Open another terminal and test the installation of PySpark

```bat
  pyspark
```

If the message states no JDK, install JDK:

[https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)


Otherwise, you should see:


```bat
Welcome to
      ____              __
     / __/__  ___ _____/ /__
    _\ \/ _ \/ _ `/ __/  '_/
   /__ / .__/\_,_/_/ /_/\_\   version 2.5.4
      /_/
```



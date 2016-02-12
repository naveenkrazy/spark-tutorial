```
                               _               _             _                    _           _ 
                              | |             | |           | |                  (_)         | |
  ___   _ __     __ _   _ __  | | __  ______  | |_   _   _  | |_    ___    _ __   _    __ _  | |
 / __| | '_ \   / _` | | '__| | |/ / |______| | __| | | | | | __|  / _ \  | '__| | |  / _` | | |
 \__ \ | |_) | | (_| | | |    |   <           | |_  | |_| | | |_  | (_) | | |    | | | (_| | | |
 |___/ | .__/   \__,_| |_|    |_|\_\           \__|  \__,_|  \__|  \___/  |_|    |_|  \__,_| |_|
       | |                                                                                      
       |_|                                                                                      
```

This tutorial provides a quick introduction to using Spark. It demonstrates the basic functionality of RDD and DataFrame API

#### Initializing Spark

```scala
val conf = new SparkConf().setAppName(appName).setMaster(master)
new SparkContext(conf)
```

Check [SparkCommon](https://github.com/rklick-solutions/spark-tutorial/blob/master/src/main/scala/com/tutorial/utils/SparkCommon.scala)

`Note:` Only one SparkContext may be active per JVM. You must stop() the active SparkContext before creating a new one.

We have tried to cover basics of Spark Core, SQL, Streaming, ML and GraphX programming contexts.

#### Spark Core
* RDD Creations
* RDD Operations
* RDD Transformations
* RDD Actions

For more information [check](https://github.com/rklick-solutions/spark-tutorial/wiki/Spark-Core)

#### Spark SQL
* Create SQL Context
* Creating DataFrames
* Creating Datasets
* Inferring the Schema using Reflection
* Programmatically Specifying the Schema
* DataFrame Operations in JSON file
* DataFrame Operations in Text file
* DataFrame Operations in CSV file
* DataFarme API
* Action
* Basic DataFrame functions
* DataFrame Operations

For more information [check](https://github.com/rklick-solutions/spark-tutorial/wiki/Spark-SQL)







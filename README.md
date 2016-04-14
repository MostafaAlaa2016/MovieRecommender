# MovieRecommender
Implementation of a basic movie recommendation system using [Apache Spark 1.6.1](http://spark.apache.org/) and the [MovieLens](http://grouplens.org/datasets/movielens/latest/) data set. This material was originally presented by me (Cliff Laschet) at [Nextbuild 2016](http://nextbuild.nl/), held at the High Tech Campus in Eindhoven. The slide deck accompanying this software is available as PDF and located in the `/slides` directory of this repo.

You can **contact** me through my [LinkedIn page](https://nl.linkedin.com/in/cliff-laschet-91164195).

##Running the pre-built artifact
An out of the box runnable artifact is provided in the `/dist` directory, and can be started by executing the command below, provided you have a recent version of Java installed on your system.

```
java -jar MovieRecommender.jar
```

##Usage
The movie recommender will start by asking your ratings for several well-known movies, after which a top 25 list of best movie picks is shown, tailored to your movie interests. 

##Using the source code directly
This software requires [Scala](http://www.scala-lang.org/) (2.10.5) and [SBT](http://www.scala-sbt.org/) (0.13.8) to be installed on your system. Using SBT, the project may be run by, in the root project directory, executing `sbt run`. This will resolve all dependencies and other setup requirements and subsequently run the main method of the source code.

A runnable standalone artifact (fat JAR) may be generated by calling `sbt assembly`, generating the artifact in the `/target/scala-2.10` directory.

##Other resources

####Machine Learning articles and videos
+ [Big Data Market Analysis](http://www.forbes.com/sites/louiscolumbus/2015/05/25/roundup-of-analytics-big-data-business-intelligence-forecasts-and-market-estimates-2015/#73d491a14869)
+ [10 surprising ML applications](http://www.lauradhamilton.com/10-surprising-machine-learning-applications)
+ [How Google keeps spam out of your inbox](http://www.smithsonianmag.com/smart-news/how-google-keeps-your-spam-out-of-your-inbox-58828900/?no-ist=)
+ [The uprise of ML in hedge funds](http://www.ibtimes.co.uk/next-generation-machine-learning-rock-stars-will-trade-google-facebook-top-secret-hedge-funds-1542209)
+ [Google's ML Research Page](http://research.google.com/pubs/MachineIntelligence.html)

####Software
+ [Apache Spark](http://spark.apache.org/)
+ [GroupLens MovieLens data sets](http://grouplens.org/datasets/movielens/)
+ [Scala](http://www.scala-lang.org/)
+ [Scala Build Tool (SBT)](http://www.scala-sbt.org/)
+ [Spark CSV module](https://github.com/databricks/spark-csv)

####Machine learning tutorials and courses
+ [Google Developers Machine Learning instructional videos (beginner, ongoing)](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
+ [Intro to Machine Learning online course (beginner)](https://www.udacity.com/course/intro-to-machine-learning--ud120)
+ [Stanford's online Machine Learning course (intermediate)](https://www.coursera.org/learn/machine-learning)
+ [Google's online Deep Learning course (advanced)](https://www.udacity.com/course/deep-learning--ud730)
+ [MLLib documentation, Spark's machine learning API](http://spark.apache.org/docs/latest/mllib-guide.html)
+ [MLlib examples](https://github.com/apache/spark/tree/master/examples/src/main/scala/org/apache/spark/examples/mllib)

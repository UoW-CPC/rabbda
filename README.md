# RABBDA project

RABBDA (Reduce Access Barriers to Big Data Analytics) is created by the [Centre of Parallel Computing](https://www.westminster.ac.uk/research/groups-and-centres/centre-for-parallel-computing) - University of Westminster.

The project objective is to provide students and practitioners access to Big Data technologies and learning material.

For that purpose Centre of Parallel Computing currently develops a Big Data environment based on Hadoop services that can be accessed by students and researchers.

Additionally, the Centre of Parallel Computing provides the required learning material to assist the learning and development process.
That material includes Hadoop services tutorials and demo applications.

The utilised services and learning material are open-source so that everyone can learn and understand how to build their own Big Data applications.

RABBDA is the first attempt to merge a Science Gateway with a KREL (knowledge repository and learning), called [SMARTEST](https://smartest-repo.herokuapp.com/)
to facilitate the comprehension of the various aspects of a portal, in this case a Big Data portal.

For more information, please review RABBDA [here](https://rabbda.readthedocs.io/).

## Portals

### University portal

The [University portal](https://github.com/UoW-CPC/rabbda-university-portal) is a proof of concept application that aims to demonstrate how Big Data can be used to create complex Big Data solutions. Additionally, by implementing various releases, we present how a project evolves through multiple iterations.

The application exports relational data from RDMBS and analyse them with Big Data technologies.
To more detail the application aims to analyse students data to answer complex scientific question related to students performance.

### Earthquakes portal
The [Earthquakes portal](https://github.com/UoW-CPC/rabbda-earthquakes-portal) is proof of concept application that aims to demonstrate how Big Data can be used to create complex Big Data solutions.
Additionally, by implementing various releases, we present how a project evolves through multiple iterations.

This demonstration utilises earthquakes data, source: [USGS science for a changing world](https://earthquake.usgs.gov).

To more detail, static data for cities and seismograph stations are being associated with earthquakes data acquired from the Rest API. The result of this process produces information such as earthquakes closest cities and seismographic stations, and links to seismographs.

## Sample solutions

* Real-time steaming twitter data to HDFS with Apache Kafka, review the solution [here](https://github.com/UoW-CPC/rabbda-kafka-twitter).
* A Extract-Transform-Load (ETL) pipeline with Apache Hive, review the solution [here](https://github.com/UoW-CPC/rabbda-hive-etl-pipeline).
* Real-time data ingestions to HDFS with Apache Flume, review the solution [here](https://github.com/UoW-CPC/rabbda-earthquakes-realtime).

## Tutorials

* Spark and Map-Reduce Jobs with Python, review the examples [here](https://github.com/UoW-CPC/rabbda-spark-MapReduce-examples.git).


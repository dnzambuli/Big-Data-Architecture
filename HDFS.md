# What is HDFS

## Solutions offered

- cost `zero licensintg and suport speeds`
- reliability `multiple copies of data`. Protects from data loss through data replication `fault tolerance`
- speed `can write up to 1 TB/s`
- storage `can store large amounts of data`
- portability `multi-platform support`
- scalability `scaled into hundreds of nodes`

## HDFS concepts
- **Block** the minimum amount of data that can be `read` or `written` and `provides fault tolerance`
- **Node** single system resposible for storig and processing data 
- **Rack** a collection of `40` to `50` nodes used a an instance

## Hadoop Distributions
- Cloudera Hadoop Distribution `cisco, masercard`
- Horton/works `samsung, spotify, eBay`
- MapR
- IBM infosphere BigInsights 
- Microsoft Azure HDInsight Cloud based

### Advantages
Support available in:
1. packaging
2. complete setup; reliability, integrated release, bug fixes
3. Life cycle building

**Hadoop Admins** delevop custim clusters for the system.
## characteristics of HDFS

- fault replication -- replication to ensure fault tolerance
- scaling - vertical or horizontal `allows for unlimited expansion`
- Rack aware - better cluster performance `readability across racks`, `uniform content within the same racks`
- heterogeneous clusters -- multiple data types
- build for large datasets -- default size for storing and reading data to ensure storage and retrieval low latency

# Big Data Frameworks

## Spark
Apache spark is n open source processing engine to 

- store

- process data in real-time

- Uses simple programming clusters

## History
**amp lab** 2009

**BSD** 2010

**apache** 2013

**Databricks** 2014 -- sort large scale data sets 

## FEATURES of SPARK

1. `Resilient Distributed Dataset` -- saves time taken reading and writing. Runs ten to hundred times faster. *Works on the ram*

immutable fault tolerant 

distributed connections
2. `in memory computing` -- data is stored in the **RAM** allows quick access and speedy analytics
3. `multi language support`
4. `failure proofing` through RDD
5. `Analysis tools` better analytics

## components of SPARK

1. SPARK core -- base engine, parallel and distributed processing
manages memory

fault recovery

scheduling and distributing and monitoring clusters

interact with storage systems
2. SPARK SQL -- process structured and semi structured data

3. SPARK Streaming
4. SPARK MLlib
5. SPARK GraphX
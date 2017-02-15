# assignment-2.4
QN 1 Explain hadoop in layman's Term
In Layman Term,it consists of 2 components
1.HDFS(for Storage)
2.MAP REDUCE(For Processing)
 1.Hadoop Distributed File System (HDFS)
The default big data storage layer for Apache Hadoop is HDFS. HDFS is the “Secret Sauce” of Apache Hadoop components as users can dump huge datasets into HDFS and the data will sit there nicely until the user wants to leverage it for analysis. HDFS component creates several replicas of the data block to be distributed across different clusters for reliable and quick data access. HDFS comprises of 3 important components-NameNode, DataNode and Secondary NameNode. HDFS operates on a Master-Slave architecture model where the NameNode acts as the master node for keeping a track of the storage cluster and the DataNode acts as a slave node summing up to the various systems within a Hadoop cluster.

2. MapReduce- Distributed Data Processing Framework of Apache Hadoop
MapReduce is a Java-based system created by Google where the actual data from the HDFS store gets processed efficiently. MapReduce breaks down a big data processing job into smaller tasks. MapReduce is responsible for the analysing large datasets in parallel before reducing it to find the results. In the Hadoop ecosystem, Hadoop MapReduce is a framework based on YARN architecture. YARN based Hadoop architecture, supports parallel processing of huge data sets and MapReduce provides the framework for easily writing applications on thousands of nodes, considering fault and failure management.
The basic principle of operation behind MapReduce is that the “Map” job sends a query for processing to various nodes in a Hadoop cluster and the “Reduce” job collects all the results to output into a single value. Map Task in the Hadoop ecosystem takes input data and splits into independent chunks and output of this task will be the input for Reduce Task. In The same Hadoop ecosystem Reduce task combines Mapped data tuples into smaller set of tuples. Meanwhile, both input and output of tasks are stored in a file system. MapReduce takes care of scheduling jobs, monitoring jobs and re-executes the failed task.
MapReduce framework forms the compute node while the HDFS file system forms the data node. Typically in the Hadoop ecosystem architecture both data node and compute node are considered to be the same.
Hive - An application that creates map-reduce and Tez jobs based on a SQL like language called HQL. 
Pig - An application that creates map-reduce jobs based on a language called Pig Latin, which is workflow driven


QN 2 EXPLAIN THE COMPONENTS OF HADOOP FRAMEWORK
Hadoop consists of four components
1.Hadoop Common
2.Hadoop Distributed File System (HDFS)
3. MapReduce- Distributed Data Processing Framework of Apache Hadoop
4.YARN
1.Hadoop Common
Apache Foundation has pre-defined set of utilities and libraries that can be used by other modules within the Hadoop ecosystem. For example, if HBase and Hive want to access HDFS they need to make of Java archives (JAR files) that are stored in Hadoop Common.
2) Hadoop Distributed File System (HDFS)
The default big data storage layer for Apache Hadoop is HDFS. HDFS is the “Secret Sauce” of Apache Hadoop components as users can dump huge datasets into HDFS and the data will sit there nicely until the user wants to leverage it for analysis. HDFS component creates several replicas of the data block to be distributed across different clusters for reliable and quick data access. HDFS comprises of 3 important components-NameNode, DataNode and Secondary NameNode. HDFS operates on a Master-Slave architecture model where the NameNode acts as the master node for keeping a track of the storage cluster and the DataNode acts as a slave node summing up to the various systems within a Hadoop cluster.
 
HDFS Use Case-
Nokia deals with more than 500 terabytes of unstructured data and close to 100 terabytes of structured data. Nokia uses HDFS for storing all the structured and unstructured data sets as it allows processing of the stored data at a petabyte scale.

3) MapReduce- Distributed Data Processing Framework of Apache Hadoop
MapReduce is a Java-based system created by Google where the actual data from the HDFS store gets processed efficiently. MapReduce breaks down a big data processing job into smaller tasks. MapReduce is responsible for the analysing large datasets in parallel before reducing it to find the results. In the Hadoop ecosystem, Hadoop MapReduce is a framework based on YARN architecture. YARN based Hadoop architecture, supports parallel processing of huge data sets and MapReduce provides the framework for easily writing applications on thousands of nodes, considering fault and failure management.
The basic principle of operation behind MapReduce is that the “Map” job sends a query for processing to various nodes in a Hadoop cluster and the “Reduce” job collects all the results to output into a single value. Map Task in the Hadoop ecosystem takes input data and splits into independent chunks and output of this task will be the input for Reduce Task. In The same Hadoop ecosystem Reduce task combines Mapped data tuples into smaller set of tuples. Meanwhile, both input and output of tasks are stored in a file system. MapReduce takes care of scheduling jobs, monitoring jobs and re-executes the failed task.
MapReduce framework forms the compute node while the HDFS file system forms the data node. Typically in the Hadoop ecosystem architecture both data node and compute node are considered to be the same. 

4)YARN
YARN forms an integral part of Hadoop 2.0.YARN is great enabler for dynamic resource utilization on Hadoop framework as users can run various Hadoop applications without having to bother about increasing workloads.

QN 3  Explain the reasons to learn Big data technologies

1.Enormous Data Generation
2. Soaring Demand for Analytics Professionals:
3.Big Data Analytics: A Top Priority in a lot of Organizations
4.Analytics: A Key Factor in Decision Making
5.The Rise of Unstructured and Semistructured Data Analytics:
6.Personal Benefits

1.Enormous Data Generation
Since the data generated these days is very large there is sufficient means to store the data AS WE HAVE means for storing data in large amounts of the order of TeraByte but still the ways we can process, retreive these data  using conventional methods will take time and cost ineffective.So this could be solved by  Distributed computing system by means of Hadoop  and Big data

2. Soaring Demand for Analytics Professionals:
Jeanne Harris, senior executive at Accenture Institute for High Performance, has stressed the significance of analytics professionals by saying, “…data is useless without the skill to analyze it.” There are more job opportunities in Big Data management and Analytics than there were last year and many IT professionals are prepared to invest time and money for the training.

The job trend graph for Big Data Analytics, from Indeed.com, proves that there is a growing trend for it and as a result there is a steady increase in the number of job opportunities.

3.Big Data Analytics: A Top Priority in a lot of Organizations
According to the ‘Peer Research – Big Data Analytics’ survey, it was concluded that Big Data Analytics is one of the top priorities of the organizations participating in the survey as they believe that  it improves the performances of their organizations.
Based on the responses, it was found that approximately 45% of the surveyed believe that Big Data analytics will enable much more precise business insights, 38% are looking to use Analytics to recognize sales and market opportunities. More than 60% of the respondents are depending on Big Data Analytics to  boost the organization’s social media marketing abilities. 
The QuinStreet research based on their survey also back the fact that Analytics is the need of the hour, where 77% of the respondents consider Big Data Analytics a top priority.

4.Analytics: A Key Factor in Decision Making

Analytics is a key competitive resource for many companies. There is no doubt about that. According to the ‘Analytics Advantage’ survey overseen by Tom Davenport, ninety six percent of respondents feel that analytics will become more important to their organizations in the next three years. This is because there is a huge amount of data that is not being used and at this point, only rudimentary analytics is being done. About forty nine percent of the respondents strongly believe that analytics is a key factor in better decision-making capabilities. Another sixteen percent like it for its superior key strategic initiatives.

5.The Rise of Unstructured and Semistructured Data Analytics:

The ‘Peer Research – Big Data Analytics’ survey clearly reports that there is a huge growth when it comes to unstructured and semistructured data analytics. Eighty four percent of the respondents have mentioned that the organization they work for are currently processing and analyzing unstructured data sources, including weblogs, social media, e-mail, photos, and video. The remaining respondents have indicated that steps are being taken to implement them in the next 12 to 18 months.

6.Personal Benefits

It includes personal benefits like high salary,skill asset etc;

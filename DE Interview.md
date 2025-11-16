Service based Company  Interview:

python:
-------
Q. https://www.youtube.com/watch?v=B84tSLggiLA&list=PLqGLh1jt697wQTamFvXx_Odlm-Wg3zbxq&index=15
Q. Filter, map reduce in python?
Q. Difference among list and tuple , set ,dict ? 
Q. How hash collision  we can stop in dictionary 
Q. Shallow vs deep copy? explain with a example ?
Q. what is higher order function? what is closure? What is decorator? What is advantage of decorator? Write custom decorator with parameter and without parameter. Where you have used decorator in your application , give example?
Q.  Generator vs iterator . Which one is more performant ? Why?
Q. File handling with scenarios based question 
Q. Focus on Python Mutithreading concept 
Q. "123a!", it should return "112233aa!!" 
Q. How to check if the given number is prime?
Q. How many points "Manish will get based on the below given point?Input is manish?
Q. Given a string find out the occurence of each character?
Q. Write code to sort list
Q. Dictionary sorting based on values?
Q. sort the array and merge it ?
Q. Print a string in reverse using java
Q. check palindrome?
Q. Max Length Palindronic substring ?
Q. Valid parenthesis
Q. All Anangram  in a list 
Q. 2 sum problem?
Q. LCS
Q. Convert Binary Tree to BST


Project:
--------
Q. Briefly introduce yourself .
Q. How to implement end to end SDLC process
Q. What do you do on daily basis in ur project?
Q. Why you want to join this company(ex google )
Q. Explain ur project architecture -(S3 bucket ->data brick->Apache Spark ->S3 )
Q. What is the volume of data you have  worked on? 
Q. What is data volume in your day to day pipeline and how to resolve scalability challenges i.e day by day data volume increases incrementally?
Ans: size of data ,source of data, pipeline how it is architected, quality of data and pipeline issue resolution , spark handling the data , version ,schema evolution etc, scalability of data handling => in config file we keep optimal size of driver and executor memory 
Q. How do you optimize a data pipeline for better performance and scalability?
Q. What is cluster configuration of ur project ? 
Q.How do you decide the number of cores ,memory and all? 
Ans: No hard and fast rule depend on data, no one can tell upfront, worst solution
Q. Suppose your Spark job is taking longer than expected, what steps would you take to debug and optimize it?
Q. Have you ever worked on a data migration project? What challenges did you face while transferring data from an on-premise database to AWS or Redshift?
Q. How to validate and monitor jobs stages in spark in production and what is the orchestarion tool you use for automation of your jobs? Ans - (we can use orchestration tool-Autosys tool, Airflow ),Spark UI access gives all view ,logs look at it .
Q. How to monitor ur spark jobs? Ans (Spark web UI)
Q. How did you handle tbs of data during ingestion in a was data pipeline where trigger can be invoked along with scheduling?
Q. How did you handle  production deployment in your project ? (How to go in higher dimension u sing , branching strategies,  )
Q. What are the challenges you faced implementing spark jobs and how did u resolve this? Ans (1. Data dedication after join 2. Upset not supported 3. Business complex use case 3. OOM 5. Spark Optimisation for TBS of data)
Q. Spark Tool Including data brick
Q. What micro service you have worked upon?(API, FastApi)

Deployment
—-----------
Q. How did you handle production deployment in your project? Ans- Expalin versioning,CI,CD,artifact movement, monitoring,logging,alerting in production env
Q. How does your deployment work for your project?
Q. CI/CD(hit,github action, jenkins) and orchestration(Airflow and step function) ? 
Q. How you take ur code in higher environment? How u push ur code changes? 
Q. How do you roll the feature to first few %age of customer to make sure whether feature is working properly or not?
Q. What are the measures you take so that your project/pipeline does not break in production ?
Q. How pipeline got created? How artifact got created? Where artefact got stored?
Q. Have you worked on security? 
Q. have you worked on docker and Kubernetes?What all things you know about Kubernetes? how Kuberenets work ?

Project Related Question:
—————————————
https://www.youtube.com/watch?v=diHUuPIaMpI&t=33s 
Infra Related 
Q1. What cluster manager you have used in project? 
Q2. What is the size of cluster? 
Q3. How you have choosen this size cluster? 
Source and Sink Related Question? 
Q1. How does your data comes to s3 bucket? 
Q2. What are the other source you have used ? 
Q3. What is the sink in your project? 
Q4. WHat is the frequency of data in source? 
Project Details in depth Question: 
Q1. WHat is the volume that you deal with 
Q2. Please explain your project in details? 
Q3. What all challenges you have faced and how did u resolve it? 
Q4. What optimisation techniques you have used and why? 
Q5. How you done spark performance optimisation and why?
Q6. Have you done Spark performance optimsation? 
Q7. Can you walk me through your spark sumbit command? 
Q8. What is size of your team? 
Code Pipeline 
Q1. How do you take youe code to higher envirnment? 
Scheduling related Question 
Q1. How do you schedule your job in production? 
Q2. What is the frequency of your job ? 
Q3. How much time it takes to run the job? 
Q4. How do you notify to the business/stake holder if your job fails? Q5. How do you reprocess the data if job fail? 
Business Related Question: 
Q1. Who is ur client ? 
Q2. What is the impact of the project on business? Q3. What is the data domain?

DE Basic :
—————
1. Project tech stake and architecture?
2. List of file format/storage format used in hive? Like  orc. avro,parquet? Explain from your project and why u have selected orc or parquet?
3. What is different between partition and bucket? When to use partition?When to use bucket? Explain with 10 record file
4. Repartition and coalesce ? Explain mechanism and performance impact?
5. How hammy output task get created in spark?
6. Write a spark word count program in pyspark? 
7. Write a program to join two table by reading file using data frame save in orc ,Avro and parquet?
8. I have two blocks in hdfs ,how many input  task count get created in spark?
9. What is default partition in MapReduce and Spark? How it is creating partition ? Tell me formula with sample?
10. Hive Bucket internal formula? 
11. Hive acid table?We are using for OLAP not OLTP?
12. How to create a hive acid table? Ans- enable txn 

Spark Architecture:
------------------
Q.Explain map reduce architecture in details? 
Q. Hadoop vs Spark architecture comparison? 
Q. What is Spark? Explain Spark Architecture? 
 (a). What is fault tolerance and how does spark handle it
 (b). Memory management and garbage collection in Spark
Q. Compare and contrast Spark vs map reduce
Q. What is the comparison between spark sql and hive in terms of performance ?Ans (In memory optimisation ,Query Optimisation ,Data format)
Q. How to create external table from internal in hive? Ans( Alter table set TBLPROPERTIES(EXTERNAL=TRUE))
Q. Partitioning vs bucketing in hive? 
Q. What is vectorisation in hive?
Q. What is the comparison between spark sql and hive in terms of performance ?Ans (In memory optimisation ,Query Optimisation ,Data format)

Spark advanced:
--------------
Q.(a). Read a csv file and infer the schema then filter the records where id> 100 and the write it in the table? 
(b). In the below goven data replace !$#@ characters with '' empty space? Ans- use case when or regular expression 
Q. Pull the data for may month from s3 location which is parition by day. Find the total running sales? sparkcontext,read,schema define,filter,predicate Optimise at every step ? We have also refund table, so just remove refuned record? Sales table is too big and refund is small? Q. Partion by and bucket by differnce. expalin with by giving one example? 
Q. Explain different tuning Config
Q. Focus on handling the corrupted data using pandas and data loading using json 
Q. explain executor and driver out of memory situtations in spark
Q. Your job is failing due to OOM (Out of Memory) on the last shuffle step — how will you debug and optimize this issue? 

Q. How would you design a scalable data pipeline to handle large datasets with real-time processing requirements? 
Q. Comparison between Parquet, Avro, ORC, CSV, Json, Delta and other possible storage methods?When to use which one? 
Q. What is parquet file and why it is fast? What is the role of portioning and when writing the data in parquet ,how do you decide partition columns?
Q. How stages are created from given query?Explain all the  4 stages in details ? 
Ans: Unresloved logical plan-> Logical Plan->Optimised logical Plan->Physical Plan-> Select Physical Plan -> RDDS 
Q. Answer following question
(a). How Spark will run this query? Select * from table1; explain every point?
Ans- I directly assume some driver and memory without asking for a table size which was one of the biggest mistake.So always clarify?
(b). How many jobs, tasks and stages will get created?
(c). What will happen if my stage fails  then how reprocessing will happens in spark?
Ans- Task Level-4 time retry; 
     Stage level- Reprocessing happen for the stage;
     Job Level- You will have to run the entire process; 
     Node down in cluster- New executor running on that executor;
(d). What will happen if I do select * from table1 limit 1. What will be impact of limit 1 on data base query engine and spark query engine? 
Ans - Entire data will not be scanned
Q. Answer following question
(a). If I have 100 gb of data in this process how many jobs ,stages and task will be created?
(b). What If I have skewness in data then how will you solve this? 
Ans- AQE,Salting 
Q. How will you repartition data to improve performance in PySpark? 
(c). What can be reason for skewness?
Q. I have 2 big table with 10 billion record in each.
 (a). How will you design the solution.
 (b) Also there is 5 millions records updates almost on daily basis. What will be memory required for this data to process within 1 hour(SLA).
Q. What optimisation techniques  you have used other than inbuilt  like re-rationing ,caching and salting ?
Ans - data filtering -> cache-> repartition ->  broadcast join if possible ->
Q. What all optimisation techniques you have used in Spark? 
Ans: Partiting,Bucketing,Multithreading(not in spark),Caching,coalescing,Broadcasting,Parquest as file format , memory optimisation based on execution plan
Q. What all optimisation techniques you have used in the database when your spark job is running slow?
Ans-  Projection pushdown and predicate pushdown reduce filtered data
Q. What is projection pruning in spark?  Show with real time example.
Ans: Projection pushdown ,Predicate pushdown
Q. What is Adapter Query Execution(AQE)?
Ans 1. Dynamically coalescing shuffle partitions ,2. Dynamically switching join strategies 3. Dynamically optimising skew joins 
Q. What is data shuffling ? Why it is  occurred and what are the techniques to resolve this? 
Ans: due to skewness. One partition , repartition and sorting 
Q. Compare and contrast broadcast join, sort-merge join and shuffle hash join ? What is broadcast join and why  it is required? 
Q. Pyspark code to perform broadcast join and conditional aggregation based on location  max(avg(salary))? 
Ans - window function+group by +broadcast join 
Q. What is shuffle ? Why Shuffling occurs? how to handle shuffling ?
Ans: join , number of job stage and task in spark
Q. How does Spark handle data shuffling, and what are some ways to reduce it?
Q. Compare and contrast cache and persist in spark? What are the different persistence levels in Spark, and when would you use them? 
Q. How to handle null in spark ? 
Ans- 1. Filtering null values 2. Replacing null values 3. Dropping null values 4. Coalesce function 
Q. What is the best way to handle null values during data transformation? 
Q. How to upsert your  data daily basis using spark?
Ans: Approach 1: we can use Hoodi or iceberg or delta lake 
     Approach 2: Step:  1. Find the column that will be unique 2. Split the data into new_records_df and update_records_df 3. Update the existing records using join 4. J union the new_records_df 
Q. How to  perform scd2 using spark? 
Q. What is checkpointing in spark? 
Q. What is serializer in spark? Ans- 1. Java Serialiser(default) 2. Kryo Serializer(recommended by spark) Q. What is unresolved relation ?
Q. What is unresolved relation in Spark?
Q. Do u know anything about graph databases?

Pyspark:
-------
2. Write a PySpark code to read CSV file from S3 Bucket and convert it into Parquet format. 
3. How would you broadcast small datasets in PySpark? 
5. Write PySpark code to remove duplicates based on multiple columns.
3. How would you broadcast small datasets in PySpark? 
4. How would you handle Data Skewness in PySpark?  
6. Write Pyspark code to implement SCD logic.

Q. Difference between RDDs, DataFrames and Datasets?
Q. What is the difference between transformations and actions in Spark? Can you give an example?
Q. Difference between narrow and wide transformation?
Q. Difference between map and flat map in spark?
Q. Difference between reduce by key and groupbykey and which is more performant and why?
Q. How does `repartition` differ from `coalesce` in Spark?
Q. Error in dynmic partition pruning? 
Q. How to handle null in spark?How to drop columns if it has null value in it? 
Ans:1. Filtering null values
    2. Replacing null values
    3. Droping rors or cols with null values
    4. Coalesce function
Q. How to upsert your data daily basis using spark? 
Ans: 
    1. Find the columns that will be unique
    2. Split the data into new_records_df and update_records_df
    3. Update the existing records using join
    4. Union the new_reords_df 
Q. Pyspark code to perform broadcastjoin and condition based on location max(avg(salary))
Q. What are the read mode and write mode in spark? 
Ans: Read mode(1.failfast , 2. dropmalformed 3. Permissive) , Write Mode(1.append , 2.overwrite,3.ignore 4.errorifexists) 
Q. spark submit command. What are main Spark submit params?
Q. Write a word count program in spark? 
Q. difference betwwen head() and take() 
Q. Regular expression in sql 
Q. Lead lag question in sql ?(code in pyspark data frame api )
Q. How to convert array column into list of columns? Write code both in athena sql and pyspark?

Q. How many records will be thre after joing thhis tables inner , left ,right, outer and anti join ? tab_1(id): 1 1 1 1 1 0 0 null 0 null null  , tab_2(id) 
Q. Pyspark code to extract data from csv file and create table on top of that?
Q. From a student table based on student id best of 3 marks using sql and avg of that for best of three? 
Ans: window_spec = Window.partitionBy("student_id").orderBy(col("marks").desc) ranked_df=student_df.withColumn("rank",row_number().over(window_spec)) best_three_df = ranked_df.filter(col("rank")<=3) result_df= best_three_df.groupBy("student_id).agg(avg(col("marks")).alias("best_of_three") result_df.show() 
Q. Pull the data for may month and find total sales? 
Ans (There was refund table too. Orders tables big refund tables small so do filtering out records then broadcast hint . And cache for optimisation hive megastore and internal of it)
Q. Write a query to fetch duplicate records from a table with employee name and salary. 
Q. How will you remove duplicate records without using DISTINCT? 
Q. If your source file is having 100 million records and only 2000 records are duplicated, how will you remove duplicates? 
Q.a. Suppose you have a table with Employee, Salary, and Department. How would you return the top 3 highest salaries from each department? 
Q.b. What will be your approach to increment salary by 10% for employees having salary less than 50K in one query? 
Q.c. Write an SQL query to find the second highest salary from an employee table.
Q.d. Write Sql Query that find out managers with at least 5 direct report 
Q.e. How would you find the 2nd highest salary from an employee table without using TOP or LIMIT? 
Q. a. Print respective manager name of emp for repective emp(new col mgr_name). EMP(id,name,mgr_id) 
 b. Who is manger and who is not? 
 c. add new column in above table with average salary for employee by department? 
 d. add new column with records having highest salary in each department? 
Q. From a student table based on student  ID best of 3 marks using sql and avg of that for best of three? 
Q. Sql query to find house from student table whose avg score > 70? score_tbl(id,score) , address_tbl(id,name,address)
Q. From a student table based on student ID best of 3 marks using pyspark and avg of that for best of three?
Q. SQL query to fins all numbers that appears at least three times consecutively 
Q. How would you identify the missing numbers between 1 to 100 from an employee ID column?
Q. Given a table with one column id dind the sum of all positive and all negative numbers? ABC table id +5,-5,-7,-2,3,10,1 
Ans: select sum(id) as id from abc where id >0 union all select sum(id) as id from abc where id<0 Q. 
Q. Given two table find out the record which are not common in both ? 
Ans- select a.id from table1 a left join table2 b on a.id=b.id where b.id is null Q. Difference between rank,dense_rank and row_nimber? Explain lead and lag function ? Q. How will you keep one column always on top?(SQL) let say US? 
Ans tbl(country,revenue) : 1. Craete a new column by giving 1 as US and 2 as rest 2. Now do all calulation and then order by newly_created_column 
Q. No of occurence in column in tbl(country,revenue) 
Q. Age bracket SQL question. tbl(name,age) . Ans- use case when statement
Q. How to convert 3 row result in one column? 
Q. Pivot Programming question? 


Datawarehouse:
--------------
Q. Compare Sql and  No Sql databases. When to choose sql and when no sql?
Ans: no-sql: 1. Schema Flexibility , Horizontal l sculling , caching and in memory storage
Q. Compare and contrast OLTP and  OLAP?
Q. Fact tables and dimensional tables properties? 
Ans- Fact Table(measurement)(1. Transaction data 2. Foreign Key 3. Data volumes). 
     Dimensional Table(context)- (1. Descriptive data 2. Primary key 3. Frequent updates 4. Smaller Data volume )
Q. Natural vs Surrogate key
Q. Snowflake vs Start Schema
Q. SCDtype- 1,2,3,4,6
Q. How did u handle scd in your  project and etc implementation?
Q. Implement scd2?
Q. How to convert SCD0 to SCD3? 
Ans- SCD0- No overrite in entire lifecycle SCD3- only limited historical data is tracked.Columns are addded in the dimension to store some historical information ,usually the current value and previous value.
Q. fact tables and dimesional tables properties? 
Ans: Fact Table- (Measurement) a. Transaction data b. Foreign Keys c. Data volume Dimesion table: (context ) a. Descriptive Data b. Primary Keys c. Frequent Upates d. Smaller Data volume 
Q. How to create a table partitioned on few columns? 
Ans: Create table DB_NAME.TABLE_NAME(ID int , Name String, City String) Partitioned By(State string , month String) ROW FORMAT DELIMITED FIELDS TERMINATED BY '|' 
Q. How will you put data into table from hdfs and local into the table?
Q. Normalisation & Denormalisation of databases 
Q. Union and UnionAll 
Q. Difference between view, materialised view and table? 
Q. Difference between rank, dense rank and row numbers? 
Q. Window Function and complex Join
Q. Pivot programming question ?

Sql:
----
Q. What is feature of no sql database? How it is different from no sql? When to use sql and when no sql. 
Ans: no-sql: 1. Schema Flexibility , Horizontal scaling , caching and in memory storage
Q. Explain inner,left,right ,outer and anti join?
Q. Indexing , types ,merit and demerit
Q. Difference between view, materialised view and table? 
Q. Difference between rank, dense rank and row numbers? 
Q. How Will You do Optimization in SQL Querry 
Q  StoreProcedure vs function vs Trigger
Q. Write Store procedure. How it is different from function ?
Q. Cursor
Q. What all optimisation techniques you have used  in database when your db is running slow?
Q. Window Function and complex Join
Q. SQL query to fins all numbers that appears at least three times consecutively 
Q. Write Sql Query that find out managers with at least 5 direct report 
Q. Regular expression in sql 
Q. How to explode array in sql 
Q. Write an SQL query to find the second highest salary from an employee table.
Q. From a student table based on student  ID best of 3 marks using sql and avg of that for best of three? 
Q. Sql to find house from student table whose avg(score)>70?
Q. How would you find the 2nd highest salary from an employee table without using TOP or LIMIT? 
Q. Write a query to fetch duplicate records from a table with employee name and salary. 
Q. How will you remove duplicate records without using DISTINCT? 
Q. Suppose you have a table with Employee, Salary, and Department. How would you return the top 3 highest salaries from each department? 
Q. What will be your approach to increment salary by 10% for employees having salary less than 50K in one query? 
Q. How would you identify the missing numbers between 1 to 100 from an employee ID column?
Q. Pivot programming question ?

ETL/ELT/Airflow/Pipeline
————-------------------
Q. Implement Apache hudi file format feature  like upset?
Q. What is volume of ur source data?
Ans: total size
Q. What all data validation is done on the data?
Ans: required columns check,Data type mismatch,Schema evolution detection and handling,Record drop or increase handling, cost reconciliation, many more exception handling at each step
Q. Why are you not storing data in parquet ?
Ans: This question ask how to decide which data  file format you will use for saving in data lake/delta lake?
Q. He asked about incremental load?
Ans: I said timestamp and hash comparison on full load
Q. Explain end to end flow of Airflow architecture? Where is dag , where it is stored, how worker picks dag task , how  dag dependency get resolved? Web server how its looks? How queues works?
Q. What is use of Scheduler in Airflow? Explain all internal component?
Q. How do u achieve scalability in ur data pipeline?
Q. Where do you go to find issues if ur pipeline fails? 
Ans:Orchestration tool(first look it), log Monitoring(superset ui),Server logs(stout and stderr),codefix
Q. Why do you not automate the pipeline in case of failure? Why there is manual intervention?What are steps required to automate  it? 
Ans: Airflow email operator
Q. What happens if your super critical  pipeline fails on weekends? What is the SLA?
Q. How do you ensure that your pipeline  is giving the correct result.
Ans: Data quality check and  handling when writing in db ,Every time check initial count i.e (reconciliation , Error Handling and Runtime checks) 

Q. How have you designed and implemented Airflow micoservices? Ans- FastApi
Q. What is ur input file for creating DAG in Airflow? 
Ans: micro service - input file ,running time ,backfill , dagger name ,task name
Q. How do u make dependency on DAG and Airflow?
Ans: 1. task Dependency on same DAG 2.  Multiple dag dependency ?
Q. How will you achieve parallelism in Airflow task? How will you take user input to do so? 
Ans- Take Nested Json.

AWS Pipeline:
--------- 
Q. What is the difference between Step function ,Airflow ,Lambda and Glue? 
Q. How did you handle tbs of data during ingestion in a aws data pipeline where trigger can be invoked along with scheduling?
Q. How will you load data from s3 into Azure redshift with all data validation checks? 
Q. How would you create an ETL Pipeline in aws to process incremental data? 
Q. Your  Pipeline is running slowly — how will you optimize it? 
Q. How will you design a parameterized pipeline for dynamic data ingestion from multiple files? 
Q. How will you monitor and debug failed  pipelines? 
Q. How will you design a parameterized pipeline for dynamic data ingestion from multiple files? 

S3:
---
Q. How to handle data using AWS S3 using cli and python? (read,write,delete,update ,rename etc)
Q. How to handle data using was s3? Ans ( how to read ,write delete, update ,rename and all the operation using python and cli)
Q. data lake , datawarehouse ,lakehouse architecture and delta lake differnece?
Q. AWS : s3 versioning and time travel

AWS Glue + S3 + Lambda:
------------------------
Q. What is SaaS ,IAAS and PaaS? What is the difference among them?
Q. Which Was service u have used? Ans- Glue,S3,lambda ,Athena,EMR,Redshift,?
Q. Difference between emr and glue ?
Q. What is AWS Glue? What are its main componenbt and their purpose?
Q. Can you explain how AWS Glue works and where it fits in a data pipeline?
Q. How Glue is  different from Databricks? 
Q. What is metstore in glue? What is its purpose?
Q. What is the role of Crawler in AWS Glue?
Q. Incremental data load handling in aws glue? 
Q. How would you optimize Glue job for large files processing?
Q. How will you read data from S3 bucket and write into another bucket in parquet using Glue Job? 
Q. How can you trigger Glue job automatically on S3 file arrival? 

AWS & Redshift Questions
——————————————
Q. What are the different ways to load data into Amazon Redshift?
Q. How does Redshift handle distribution styles, and how do you decide which one to use?

Streaming:(Kafka+Spark+Flink)
——————-----------------------
Q. How Kafka manage offset  
Q. Kafka Related Streaming question like topic ,how data consumes in ur system
Q. Did You implement streaming pipeline ? 
Q. If my Kafka consumer is reading slow then how will you handle back pressure?
Q. He asked about incremental load. I said streming and he asked me about checkpointing in streaming?
Q. How checkpointing work in streaming?How you have used ? Where you are validating ? How the folder of check pointing forms ?Who creates these logs?
Q. System design to build streaming solution?

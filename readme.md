https://www.youtube.com/watch?v=sTk1hflzPYc&list=PLTsNSGeIpGnGjaMSYVlidqVWSjKWoBhbr&index=25 
HCL: 
https://www.youtube.com/watch?v=Ak_F2OC4wLg&t=18s 
https://www.youtube.com/watch?v=OX4UfThjQ6c&t=6s 
https://www.youtube.com/watch?v=CyTDr-ZZ2EU&t=12s 

1. Can you Introduce yourself? 
-------------------------------
Thank you for giving me opportunity to introduce myself 

My name is Jyotsna and I am from Bihar.
Currently I am working as a data engineer at HCL .HCL is a consulting firm which primarily work is us health care domain.
Overall I have 3 years of experience out of which I am with zs from last 2 years. 
Currently i am leading a team of three members un my project .
The my tech stack are Python,Sql,SPark,Hadoop,Hive,Impala,Teradata.
For project management we are using JIRA .
For CI/CD github action , jenkins and aws devops we are using.

2. Explain your project architecture? 
Ans. 
a. Briefly expalin about your data domain and aim of project
- I have been working with client who mostly deals with pharam . Our project we were working with doctor data. Tha aim of the project is to find of 
who is prescribing our product and how often he is prescribing the product 
b. Briefly explain about end to end data flow 
- First we get datafrom data provider vendors which is in different s3 bucket .using shell scripting data 
is moved to developer accessed s3 folder . then we load the required data into our spark care
cluster .After processing we push into hive database/data are house.
c. Briefly explain about tech stack used 
- coming to tech stack used for this process are , spark , python , airflow ,dms , step function a,redshift ,lambda ,
s3 , iceberg .

Q. What is the volume of data that you have worked on?
Q. What is the cluster configuration for your project?
Ans- We had 2 TB cluster dedicated for development. There was multiple queues in there?
Q. How to monitor your spark jobs?
- Spark web UI how to use 
Q. How to validate and monitor jobs stages in spark in production ?
Q. What is orchestraion tool you use for automation of your jobs?
Q. What are the challenges you faced implemnting Spark Jobs and how did u resolve this?
Ans:
1. Data Duplication after join 
2. Upsert not Supported 
3. Business complex use case 
4. Out of memeory error(oom)
5. Spark optimisation for TBs of data 
Q. How to process 1 TB of data in spark?
Q. Design a datawarehouse problem? Q- fact,dimesnsion,star,snowflake,join,key,storage 

DS/Algo
------
https://www.youtube.com/watch?v=B84tSLggiLA&list=PLqGLh1jt697wQTamFvXx_Odlm-Wg3zbxq&index=15 
Q. list vs tuple vs set vs dict 
Q. copy vs deep copy with example
Q. decorator with code 
Q. Generator vs iterator . WHich one is more performant ?

Q. check palindrome?
Q. "123a!", it should return "112233aa!!"
Q. How to check if the given number is prime?
Q. dictionary sorting based on values
Q. How many points "Manish will get based on the below given point?
Q. Given a string find out the occurence of each character? 
Q. Anagram 
Q. 2 sum problem 
Q. sort the array and merge it ?


S3:
--
Q. How to handle data using AWS S3 using cli and python? (read,write,delete,update ,rename etc)

Pyspark:
--------
Q. Transformer vs action 
Q. Difference between narrow and wide transformation?
Q. Difference between reduceByKey and groupByKey?Which one is more performant and why?
Q. Error in dynmic partition pruning?
Q. spark submit command 
Q. Write a word count program in spark?
Q. difference betwwen head() and take()
Q. WHat are the read mode and write mode in spark?
Ans- Read mode(1.failfast , 2. dropmalformed 3. Permissive) , Write Mode(1.append , 2.overwrite,3.ignore 4.errorifexists)
Q. How to convert array column into list of columns? 
Q. Pyspark code to extract data from csv file and create table on top of that?
Q. How to upsert your data daily basis  using spark?
Ans- 
1. Find the columns that will be unique 
2. Split the data into new_records_df and update_records_df 
3. Update the existing records using join 
4. Union the new_reords_df 
Q. Pyspark code to perform broadcastjoin and condition based on location max(avg(salary))
Q. From a student table based on student id best of 3 marks using sql and avg of that for best of three?
Ans:
window_spec = Window.partitionBy("student_id").orderBy(col("marks").desc)
ranked_df=student_df.withColumn("rank",row_number().over(window_spec))
best_three_df = ranked_df.filter(col("rank")<=3)
result_df= best_three_df.groupBy("student_id).agg(avg(col("marks")).alias("best_of_three")
result_df.show()
Q. How to handle null in spark?How to drop columns if it has null value in it?
Ans- 
1. Filtering null values
2. Replacing null values 
3. Droping rors or cols with null values 
4. Coalesce function 
Q. Read the df ,define schmea,filter out the emp earning less the 20k, add a column bonus 10% for each emp and calculate the total salary afterbonus.Save the final df as parquet?
 emp_df(name,dept,salary)
Q. Read a csv file and infer the schema then filter the records where id> 100 and the write it in the table? 
Q. In the below goven data replace !$#@ characters with '' empty space?
Ans- use case when or regular expression 
Q. How to convert 3 row result in one column?
Q. Pivot Programming question?
Q. Pull the data for may month from s3 location which is parition by day. Find the total running sales? sparkcontext,read,schema define,filter,predicate Optimise at every step ? We have also refund table, so just remove refuned record? Sales table is too big and refund is small? 
Q. Partion by and bucket by differnce. expalin with by giving one example? 
Spark:
------
Q. Explain difference beteen different file format(csv,json,parquet,orc,avro) .When to use which one?
Q.Explain map reduce architecture in details?
Q. Hadoop vs Spark architecture comparison?
Q. What is comparison between spark sql and hive?
Ans: 
a. In memoey comparison 
b. Query Optimisation
c. Data Format(ORC , vs multi format)
- How job create ,stage create 
Q. How Query get created. list all the four stages? Ans- Unresloved logical plan-> Logical Plan->Optimised logical Plan->Physical Plan-> Select Physical Plan -> RDDS
Q. What is shuffle and how to handle this?
Q. What is data shuffling ? Why it is occured and what are the techniques to resolve this?
Q. What is broadcast join and why it is required ?
Q. What is projection pruning? Ans- Projection pushdown and Predicate Pushdown 
Q. What is predicate pushdown and AQE. Show with real time examples?
Ans- Select * from emp where salary > 40000
Q. Cache vs Persist
Q. How to monitor your spark jobs?
- Spark web UI how to use 
Q. How AQE works?
Ans - 
1. Dynamically coalescing shuffle partitions 
2. Dynamically switching join strategies 
3. Dynamically optimising skew joins 
Q. What is checkpointing in spark?
Q. What is serializer in spark? Ans- 1. Java Serialiser(default) 2. Kryo Serializer(recommended by spark) 
Q. What is unresolved relation ? 
Sql:
---
Q. What is feature of no sql db? How it is different from relation db?
Ans- 1. Schema Flexibility 2. Horizontal Scalabality 3. Caching and in-memory storage 
Q. Sql query to find house from student table whose avg score > 70?
score_tbl(id,score) , address_tbl(id,name,address)
Q. How many records will be thre after joing thhis tables inner , left ,right, outer and anti join 
tab_1(id) , tab_2(id)
1            1 
1            1
1            0
0            null 
0
null 
null 
Q. a. Print respective manager name of emp for repective emp(new col mgr_name). EMP(id,name,mgr_id)
b. Who is manger and who is not?
c. add new column in above table with average salary for employee by department?
d. add new column with records having highest salary in each department?
Q. Given a table with one column id dind the sum of all positive and all negative numbers? ABC table id +5,-5,-7,-2,3,10,1
Ans: select sum(id) as id from abc where id >0 union all select sum(id) as id from abc where id<0
Q. Given two table find out the record which are not common in both ?
Ans- select a.id from table1 a left join table2 b on a.id=b.id where b.id is null 
Q. Difference between rank,dense_rank and row_nimber? Explain lead and lag function ?
Q. How will you keep one column always on top?(SQL) let say US?
Ans tbl(country,revenue) : 1. Craete a new column by giving 1 as US and 2 as rest 2. Now do all calulation and then order by newly_created_column
Q. No of occurence in column in tbl(country,revenue)
Q. Age bracket SQL question. tbl(name,age) . Ans- use case when statement 
Q. Pivot Programming question?
Q. Do you know anything about graph databaes ? 


DB Modelling:
--------------
Q. What is fact table and star schema in DW?
Q. How did u handle scd in ur project and etl implmentation?
Q. How to convert SCD0 to SCD3?
Ans- 
SCD0- No overrite in entire lifecycle
SCD3- only limited historical data is tracked.Columns are addded in the dimension to store some historical information ,usually the current value and previous value. 
Q. fact tables and dimesional tables properties?
Ans: 
Fact Table- (Measurement)
a. Transaction data 
b. Foreign Keys 
c. Data volume 
Dimesion table: (context )
a. Descriptive Data 
b. Primary Keys 
c. Frequent Upates 
d. Smaller Data volume 
Q. How to create a table partitioned on few columns?
Ans 
Create table DB_NAME.TABLE_NAME(ID int , Name String, City String)
Partitioned By(State string , month String) ROW FORMAT DELIMITED FIELDS TERMINATED BY '|'
Q. How will you put data into table from hdfs and local into the table?

Hive:
-----
Q. How to create external table from internal table?
Ans - ALTER TABLE <table> set TBLPROPERTIES('EXTERNAL'='TRUE')
Q. What is vectorization in hive? 
Q. 

CI/CD/IAC
==========
Q. How did you handle production deployment in your project?
Ans- Expalin versioning,CI,CD,artifact movement,  monitoring,logging,alerting in production env


Project Related Question:
-------------------------
https://www.youtube.com/watch?v=diHUuPIaMpI&t=33s 
Infra Related
Q1.  What cluster manager you have used in project?
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
Q4. How do you notify to the business/stake holder if your job fails?
Q5. How do you reprocess the data if job fail?
Business Related Question:
Q1. Who is ur client ?
Q2. What is the impact of the project on business?
Q3. What is the data domain?
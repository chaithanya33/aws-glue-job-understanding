# aws-glue-job-understanding

# AWS GLUE : IS A SERVERLESS ETL SERVICE ON AWS PROVIDE INFRA

SIMPLE WORDS : IS USED TO EXTRACT DATA , clean/transform it and load it to another place automatically without managing servers


ETL : (EXTRACT TRANSFORM LOAD ) || data sources in multiple locations || SFTP||  IN SINGLE IN ONE PLACE 
 

EXAMPLE: 

1) EXTRACT SOURCES : S3 , DATABASES , JSON ,CSV,EXECEL 

2) TRANSFORM : CLEAN DATA , REMOVE DUPLICATES , CHANAGE DATA TYPES , APPLY BUSINESS RULES AND JOIN DATA SETS

3) LOAD : WRITE CLEANED DATA , S3, DATA LAKE, DATA ANALYTICS SYSTEMS 


__________________________________________________________________________

   #  
BEFOR AND AFTER GLUE :

BEFORE :
 1) DATA IN MANYA PLACES
2) NEED SPARK CLUSTER
3) HEAVY SETUP AND MAINTANCE
4) COSTLY AND SLOW 

AFTER GLUE :

1) NO CLUSTER SETUP
2) NO SERVER MANAGEMENT
3) AUTOMATIC SCALLLING
4) PAY ONLY WHEN JOB RUNS


_________________________________________________________________________
AWS GLUE COMPONENTS :

1)GLUE CATALOG : A CENETRAL MEATA DATA STORE 

EX: TABLE NAMES , FILE LOCATIONS ,DATA TYPES AND COLUMN NAMES



2) GLUE CRAWLER: SCANS DATA AUTOMATICALLY AND DATA SCEHMAS AND CREATE TABLES IN DATA CATELOG (SOURCE TO DESTINATION) EVEN CHANGING FORMATS SO PIPELINES DOES NOT FAIL

EX: AUTO DETECTING COLOUMNS IN CSV AND JSON FILES


3) GLUE joB : actual etl code uses apeche spark and written in pyspark



4) glue trigger : runs glue jobs automatically based on events 

______________________________________________________________________

how it works step by step 


1) data stored in some destination ( raw data)

2) glue crawler scans data

3) schema stored in glue catalog

4) glue jobs reads data

5) data cleand  & transformed

6) output stored in our destination

________________________________________________________________________




















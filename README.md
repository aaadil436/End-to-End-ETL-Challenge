# End-to-End-ETL-Challenge

ETL CHALLENGE

1)'data.zip' contains 8 tables in .tbl format and it is typically used to save tabular data in an optimized way for computer programs.

2)The code that would read the .tbl files and will load it into the schema given in ddl.sql file is attached as 1.py.

3)Based on the type of data given, the queries to be executed and the business processes identified from erd diagram. I designed the star schema model with 1 fact table and 4 dimension tables.I denormalised tables as we dont want the join operations during the query runtime. Fact-Dimension relationship diagram attached.

4)The code has been scripted which will read the data from .tbl file and after transforming it, will load it into the star schema. The 2.py contains the code.

5) The pipeline has been scheduled with the frequency of 2hrs which is the common practice. I started an infinite loop and put a sleep command in it with the frequency of 2 hours, following by the execution of code. Scheduling code has been attached as Scheduling.ipynb.

6) The code is super flexible. There are a lot of options available ranging from AWS, GCP and Azure to deploy the code. It can also be deployed in the form of API or Service or Event or Webapp.

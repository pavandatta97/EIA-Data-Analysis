Understanding Your Data Files:
🌍 Database Context
You are working with a structured energy dataset comprising 6 CSV files that have been imported into a MySQL database named energy. These tables include Dataset: 
●	country (central table)
●	consumption
●	production
●	emission
●	gdp_ppp
●	population
Each of the tables (except country) has a foreign key referencing the country table's country column

Challenges:
-	The project demands you to develop a perspective of your own, 
-	You will find that many questions have different ways to be solved,
-	Your job is to have a reasoning behind why you have chosen to solve the question in that particular way.
Refer the below:
country (1) → (many) emission_3

country (1) → (many) population

country (1) → (many) production

country (1) → (many) consumption

country (1) → (many) gdp_3

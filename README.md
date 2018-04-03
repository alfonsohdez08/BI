# Data Warehouse Scripts (SqlDBM)

This repository stores all scripts related to the article [Bi Data Modeling with SqlDBM](http://blog.sqldbm.com/bi-data-modeling-with-sqldbm/)
from SqlDBM blog. The following information gives a brief description of each script:

- **PointSalesCreationScript.sql:** this script has a single purpose which it's create the OLTP database and populate it. The first half of the script
it's focused on the database creation, notice that all those statements related to the database creation were generated from SqlDbm tool
by using one its feature. The other half contains a bunch of INSERT statements for populate the database. All this data come from the
AdventureWorks database.

- **DwhScript.sql:** it creates the Data Warehouse from the OLTP schema builded above.

# PublicationsIndustries

> This is a project utilizing Microsoft SQL Server, Visual Studio and related technologies to deliver a business intelligence solution. A business intelligence solution is a collection of objects that allows data to be turned into useful information. The following steps will serve as a guideline in achieving this objective.

## Step One: Interview and identify data
The process of designing your solution begins with interviewing your client to determine what type of information is needed. he answers to these questions allow you to better locate the data necessary for your solution. Once the data is located, the next step is to decide how much of it is relevant to your needs. You also need to decide whether your data’s current location is sufficient for your BI solution’s needs or whether you must copy some or all of the data to a more appropriate location.

## Step Two: Plan The BI Solution
Projects must be planned and documented before creating a working BI solution. This step involves creating a description of what your solution will accomplish, documenting the source and the destination objects, and beginning the formal documentation. A solution’s formal document can be laid out with common tools such as Microsoft Excel or even Microsoft Word. hese Excel or Word documents can then be taken back to the client for approval. Once approved, these documents will become an outline that can be worked with much like a blueprint. You then create Visual Studio projects that become the building blocks of your BI solution from these blueprints.

## Step Three: Create A Data Warehouse
A data warehouse database is designed and implemented, demonstrating star versus snowflake dimensions and creating fact and dimension tables. 

## Step Four: Create an ETL Process
This entails extracting the data from its original location, transforming the data to be consistent with your new data warehouse design, and loading the data into the new data warehouse location.

## Step Five: Create Cubes
Cubes, which can be thought of as a set of report tables combined into a single object are constructed and configured.

## Step Six: Create Reports
The end goal of a BI solution is to convert data into usable information, and that information is routinely represented within reports. Here, views and stored procedures are created that select data from one or more OLTP tables and use these as the source for all your reports.

## Step Seven: Test and tune the Solution
Once you have built your first reports, you need to test those reports for accuracy, visual consistency, and performance. Important performance tuning techniques are covered to ensure reports run quickly for end users. A number of ways to plan and implement testing procedures is also included.

## Step Eight: Approve, Release and Prepare
At the end of the solution development cycle, you need to package and deploy your documents, scripts, databases, and reports. You also need to create user documentation, as well as train your users to use your newly developed BI solution.
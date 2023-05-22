**Problem Statement** – A music streaming company wants to :

To provide personalized recommendations or insights to users based on the songs they listened to during a specific session and item index to enhance user experience, improve song recommendations, or analyze user behavior patterns.

To provide the users with a chronological list of songs they listened to during a session, including information about the artists and the user's name. This information could be used for generating personalized recommendations, analyzing user preferences, or creating personalized marketing campaigns.

To identify users who listened to a specific song and use that information for targeted marketing, personalized recommendations, or collaborative playlists by connecting users with similar music preferences.

**Proposed Solution** – To address the above use cases, below are the queries following which we will build out data model:

Give the artist, song title and song's length in the music app history that was heard during sessionId = …, and itemInSession =…

Give only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = …, sessionid = …

Give every user name (first and last) in my music app history who listened to the song ‘…’

**Dataset details:**
30 days of event data from a music app stored as csv in the working directory 

**Plan to Execute:  **

Creating list of file paths to process original event csv data files
Processing the files to create the data file csv that will be used for Apache Cassandra tables
Working with the CSV file titled event_datafile_new.csv, located within the Workspace directory
Creating a Cluster
Creating Keyspace
Setting Keyspace
With Apache Cassandra modelling the database tables on the queries we want to run
Verify that the data have been inserted into each table
Drop the tables before closing out the sessions
Close the session and cluster connection

**Tools Used:**

Cassandra DB: 
Cassandra is a highly scalable, distributed, and NoSQL database management system designed to handle large amounts of structured and semi-structured data across multiple commodity servers. It was initially developed by Facebook and later open-sourced. Cassandra is designed to provide high availability and fault tolerance with no single point of failure.

Python Cassandra driver: 
The Python Cassandra driver is a library that allows Python developers to interact with Cassandra databases from their Python applications. It provides an interface to connect to a Cassandra cluster, execute queries, and retrieve data.

Cassandra Query Language:  
Cassandra Query Language (CQL) is a query language specifically designed for working with Apache Cassandra databases. It is similar to SQL (Structured Query Language) but with some differences to accommodate the unique data model and distributed architecture of Cassandra.

Pandas:  
Pandas is a popular open-source data manipulation and analysis library for Python. It provides data structures and functions to efficiently manipulate and analyze structured data, such as tabular data.

csv:  
Python package that provides functionality for reading and writing CSV (Comma-Separated Values) files.
![image](https://github.com/gaurawtri/DE/assets/109141229/125a4cfb-1953-4309-9a63-03829f564845)

![Uploading image.png…]()

![image](https://github.com/gaurawtri/DE/assets/109141229/3c1dc638-4739-4142-9040-a3a5c1f283af)


![image](https://github.com/gaurawtri/DE/assets/109141229/670aacd2-37c6-4e69-9b9c-c3a66ff61961)


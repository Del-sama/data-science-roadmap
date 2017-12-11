# Fundamentals
## 1_Linear Algebra and Matrices
#### Linear Algebra
* Linear algebra is the branch of mathematics concerning vector spaces and linear mappings between such spaces. It includes the study of lines, planes, and subspaces, but is also concerned with properties common to all vector spaces. - [Wikipedia](https://en.wikipedia.org/wiki/Linear_algebra)
#### Matrices
* Two-dimensional array of numbers.
* Can be represented as a list of lists
#### Basic Operatons
* [Addition](https://en.wikipedia.org/wiki/Matrix_addition)
* [Scalar multiplication](https://en.wikipedia.org/wiki/Scalar_multiplication)
* [Transpose](https://en.wikipedia.org/wiki/Transpose)
#### Resources
* Data Science from Scratch - Chapter 4
* [Linear Algebra, from UC Davis](https://www.math.ucdavis.edu/~linear/linear-guest.pdf)
* [Khan Academy - Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
* [Khan Academy - Matrices](https://www.khanacademy.org/math/precalculus/precalc-matrices)

## 2_Hash functions, Binary tree, O(n)
#### Hash Functions
* A hash function is any function that can be used to map data of arbitrary size to data of fixed size. - [Wikipedia](https://en.wikipedia.org/wiki/Hash_function)
* Hash functions has a list of functions which include - comparing large amounts of data, Indexing data, generating random strings - [Stackoverflow question](https://stackoverflow.com/questions/506029/whats-the-purpose-in-hashing-information).
#### Binary tree
* A binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child. - [Wikipedia](https://en.wikipedia.org/wiki/Binary_tree)
![Binary tree](https://camo.githubusercontent.com/38340edffe661998f395184c2ac1578aea636788/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f662f66372f42696e6172795f747265652e737667)
#### O(n)
* In computer science, big O notation is used to classify algorithms according to how their running time or space requirements grow as the input size grows. - [Wikipedia](https://en.wikipedia.org/wiki/Big_O_notation)
* Big O notation describes the efficiency of an algorithm.
* Algorithms are judged by either their space complexity (how much working storage an algorithm needs) or time complexity (how much time it takes an algorithm to run).
#### Resources
* [Hashing strings with Python](https://www.pythoncentral.io/hashing-strings-with-python/)
* [Python tutorial: Hashing](http://www.bogotobogo.com/python/python_hash_tables_hashing_dictionary_associated_arrays.php)
* [Implementing Binary trees in Python](https://pythonschool.net/data-structures-algorithms/binary-tree/)
* [Big O notation for the mathematically impaired](https://medium.com/@Del_sama/big-o-notation-for-the-mathematically-impaired-91a4df1da44b)
## 3_Relational Algebra, DB basics
#### Relational Algebra
* Relational database systems are expected to be equipped with a query language that can assist its users to query the database instances. There are two kinds of query languages − relational algebra and relational calculus.
* Relational algebra is a procedural query language, which takes instances of relations as input and yields instances of relations as output. It uses operators to perform queries. An operator can be either unary or binary. They accept relations as their input and yield relations as their output. - [Tutorial Point](https://www.tutorialspoint.com/dbms/relational_algebra.htm)
* Fundamental operations:
  * [Select](https://en.wikipedia.org/wiki/Selection_(relational_algebra))
  * [Project](https://en.wikipedia.org/wiki/Projection_(relational_algebra))
  * [Union](https://en.wikipedia.org/wiki/Union_(set_theory))
  * [Set difference](https://en.wikipedia.org/wiki/Complement_(set_theory)#Relative_complement)
  * [Cartesian product](https://en.wikipedia.org/wiki/Cartesian_product)
  * [Rename](https://en.wikipedia.org/wiki/Rename_(relational_algebra))
  
#### DB Basics
* Database is a persistent repository of data stored in a computer. The data represent recorded information. By persistent we mean that the data remain available indefinitely, after the software applications that use or create the data are closed, and even when the computer systems on which the data are stored reboot or crash due to software or hardware failures.
* A database management system (DBMS) is a software system specifically designed to hold databases. We usually reserve the term database for an information repository maintained in a database management system.

#### Resources
* [Introduction to DB](http://www.cs.ubc.ca/nest/dbsl/intro.html)
* [Wikiversity](https://en.wikiversity.org/wiki/Introduction_to_Databases)

## 4_Inner, Outer, Cross, Theta Join
## 5_CAP Theorem
* The CAP theorem is a tool used to makes system designers aware of the trade-offs while designing networked shared-data systems. CAP has influenced the design of many distributed data systems. It made designers aware of a wide range of tradeoffs to consider while designing distributed data systems. - [dzone.com](https://dzone.com/articles/understanding-the-cap-theorem)
* The theorem states that networked shared-data systems can only guarantee/strongly support two of the following three properties:

   * Consistency - A guarantee that every node in a distributed cluster returns the same, most recent, successful write. Consistency refers to every client having the same view of the data. There are various types of consistency models. Consistency in CAP (used to prove the theorem) refers to linearizability or sequential consistency, a very strong form of consistency.
  * Availability - Every non-failing node returns a response for all read and write requests in a reasonable amount of time. The key word here is every. To be available, every node on (either side of a network partition) must be able to respond in a reasonable amount of time.
  * Partition Tolerant - The system continues to function and upholds its consistency guarantees in spite of network partitions. Network partitions are a fact of life. Distributed systems guaranteeing partition tolerance can gracefully recover from partitions once the partition heals.
## 6_Tabular Data
* For most people working with small amounts of data, the data table is the fundamental unit of organization.  The data table, arguably the oldest data structure, is both a way of organizing data for processing by machines and of presenting data visually for consumption by humans.  Elementary students learn how to organize data into rows and columns at a very early age while high school students master the intricacies of spreadsheets with MS Excel or OpenOffice Calc.  Even RDBMS (Relation Data Base Management Systems) have the data table as their fundamental unit of organization.
* Every row has the same set of column headers. If any row is lacking information for a particular column a missing value must be stored in that cell. - [mazamascience.com](http://mazamascience.com/WorkingWithData/?p=254)
## 7_Entropy
* In information theory, entropy measures how difficult it is to ZIP a file, i.e. how poorly a lossless compressor performs. This is because Claude Shannon based his definition of entropy upon the probabilities of seeing various outcomes such as various strings of bits. [Entrophttp://www.datascienceassn.org/content/entropy-vs-valuey vs value](http://www.datascienceassn.org/content/entropy-vs-value)
## 8_Data Frames and Series
* A DataFrame is a Dataset organized into named columns. It is conceptually equivalent to a table in a relational database or a data frame in R/Python, but with richer optimizations under the hood. DataFrames can be constructed from a wide array of sources such as: structured data files, tables in Hive, external databases, or existing RDDs. 
* Series is a one-dimensional labeled array capable of holding any data type (integers, strings, floating point numbers, Python objects, etc.). 
## 9_Sharding
* A database shard is a horizontal partition of data in a database or search engine. Each individual partition is referred to as a shard or database shard. Each shard is held on a separate database server instance, to spread load.

Some data within a database remains present in all shards, but some appears only in a single shard. Each shard (or server) acts as the single source for this subset of data.
* Sharding is a type of database partitioning that separates very large databases the into smaller, faster, more easily managed parts called data shards.
## 10_OLAP
* OLAP is an acronym for Online Analytical Processing. OLAP performs multidimensional analysis of business data and provides the capability for complex calculations, trend analysis, and sophisticated data modeling. It is the foundation for many kinds of business applications for Business Performance Management, Planning, Budgeting, Forecasting, Financial Reporting, Analysis, Simulation Models, Knowledge Discovery, and Data Warehouse Reporting. OLAP enables end-users to perform ad hoc analysis of data in multiple dimensions, thereby providing the insight and understanding they need for better decision making. 
* [OLAP tutorial](http://olap.com/learn-bi-olap/tutorials/)
## 11_Multidimensional Data Model
* An Analysis Services multidimensional solution uses cube structures for analyzing business data across multiple dimensions. Multidimensional mode is the default server mode of Analysis Services. It includes a query and calculation engine for OLAP data, with MOLAP, ROLAP, and HOLAP storage modes to balance performance with scalable data requirements. [docs.microsoft.com](https://docs.microsoft.com/en-us/sql/analysis-services/multidimensional-models/multidimensional-models-ssas)
## 12_ETL
* ETL (Extract, Transform and Load) is a process in data warehousing responsible for pulling data out of the source systems and placing it into a data warehouse.
## 13_Reporting vs BI vs Analytics
* The key difference between analytics and BI is that the former has predictive capabilities, whereas the latter has traditionally been based on providing analysis of historical data.
* 
Reporting takes factual data and presents it.  There’s no judgement or insight added. People can, of course, derive insight from reports, but that’s up to them.
## 14_JSON AND XML
* JSON is a syntax for serializing objects, arrays, numbers, strings, booleans, and null. It is based upon JavaScript syntax but is distinct from it: some JavaScript is not JSON, and some JSON is not JavaScript. 
* [MDN - JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
* XML is a markup language similar to HTML. It stands for Extensible Markup Language and is a W3C recommended specification as a general purpose markup language. This means, unlike other markup languages, XML is not predefined so you must define your own tags. The primary purpose of the language is the sharing of data across different systems, such as the Internet.
* [MDN - XML](https://developer.mozilla.org/en-US/docs/XML_introduction)
## 15_NoSQL
* NoSQL is an approach to database design that can accomodate a wide variety of data models, including key-value, document, columnar and graph formats. NoSQL, which stand for "not only SQL," is an alternative to traditional relational databases 
* [mongodb.com](https://www.mongodb.com/nosql-explained)
## 16_Regex
* Regular Expressions (sometimes shortened to regexp, regex, or re) are a tool for matching patterns in text.
* [regexone - Python](https://regexone.com/references/python)
* [learnpython.org](http://www.learnpython.org/en/Regular_Expressions)
## 17_vendor Landscape
## Env Setup



**M001: MongoDB Basics**

**LAB’s : Chapter 1: What is MongoDB?**

1. Quiz: What is MongoDB?

Why is MongoDB a NoSQL database?

Ans:

**Because it does not utilize tables, rows and columns to organize data.**

This is correct.

NoSQL means that the database does not employ tables, rows and columns for data organization,

which is true about MongoDB.

**Because it uses a structured way to store and access data**

This is correct.

A database implies that there is a structured way to store and organize data.

2.What is the MongoDB Database?

Problem: Select the statements that together help build the most complete definition of the MongoDB

database:

Ans:

**MongoDB database is an organized way to store and access data.**

This is correct.

This is a general definition of a database and applies to the MongoDB database as well as to other

databases out there.

**MongoDB is a NoSQL database that uses documents to store data in an organized way.**

This is correct.

When we specify what kind of database MongoDB has, we can classify it as NoSQL because it does

not employ related tables of data to store information, and it instead uses documents.

3.What is a Document?

Problem: In MongoDB how does a document relate to a collection?

Ans:

**Collections consist of many documents.**

This is correct.

A single collection in MongoDB consists of one or many documents.





4.What is a Document?

Problem: In a MongoDB Document what is the role of fields and values?

Ans:

**A field is a unique identifier for a specific datapoint.**

This is correct.

You can not have duplicate field names within the same level of a single document, which is

why they are unique identifiers for a specific datapoint.

**Each field has a value associated with it.**

This is correct.

Data is organized in field-value pairs, so each field has a value associated with it.

5.What is Atlas?

Problem: How is MongoDB Atlas related to MongoDB the Database?

Ans:

**They are both MongoDB products.**

This is correct

**Atlas has many tools and services within it that are built specifically for the MongoDB**

**Database.**

This is correct.


<hr>


**LAB’s : Chapter 2: Importing, Exporting, and Querying Data**

1.Quiz: What is JSON?

Problem: Which of the following documents is correct JSON?

Ans:

**{"name" : "Devi", "age": 19, "major": "Computer Science"}**

This is correct.

The document starts and ends with curly brackets, all field names are enclosed in quotes, all

field:value pairs are separated by commas.

2.JSON vs. BSON Problem:

Write BSON or JSON in the numbered blanks in the following sentences to make them true:

MongoDB stores data in \_\_\_\_\_ , and you can then view it in \_\_\_\_\_

\_\_\_\_\_ is faster to parse and lighter to store than \_\_\_\_ .

\_\_\_\_\_\_ supports fewer data types than \_\_\_\_\_ .

Ans :

MongoDB stores data in **BSON** , and you can then view it in **JSON** .

**BSON** is faster to parse and lighter to store than **JSON** .

**JSON** supports fewer data types than **BSON .**

3.Import and Export Problem: Which of the following commands will add a collection that is stored

in animals.json to an Atlas cluster?

**Ans:**

**mongoimport**

This is correct.

mongoimport can import data from JSON, and other supported non BSON formats

4.Data Explorer Problem:

In the sample\_training.trips collection a person with birth year 1961 took a trip that started at

"Howard St & Centre St".

What was the end station name for that trip?

Copy and paste your answer from the Atlas UI to the response text box. The station name should be

in a single set double quotes, exactly as it is in the Data Explorer.

Ans:

**"South End Ave & Liberty St"**





The query used to get this answer is: COPY {"start station name" : "Howard St & Centre St", "birth

year" : 1961} After the query is issued using the FIND button only one document will be returned.

You will find the answer by looking at the value of the "end station name" field.

5.Find Command Problem:

What does it do in the mongo shell?

Ans:

**Iterates through the cursor results**

This is correct.

The rest of the options are silly.

6.The mongo shell Problem:

Which of the following statements are true about the mongo shell?

Ans:

**It is a fully functioning JavaScript interpreter.**

This is correct.

mongo shell is a fully functioning JavaScript interpreter, which means that you can create things like

JavaScript functions and variables in it.

**It allows you to interact with your MongoDB instance without using a Graphical User**

**Interface.**

This is correct.

There are other means of interacting with the database, such as through the Atlas UI, which is more

visually supportive than the mongo shell.


<hr>


**LAB’s : Chapter 3: Creating and Manipulating Documents**

1.Quiz: ObjectId Problem:

How does the value of \_id get assigned to a document?

Ans:

**It is automatically generated as an ObjectId type value.**

This is correct.

When inserting a document via the Data Explorer in Atlas, the \_id value is already generated as an

ObjectID type, while the rest of the fields are not.

**You can select a non ObjectId type value when inserting a new document, as long as that value**

**is unique to this collection.**

This is correct.

MongoDB generates a value, so that there is one just in case. You can definitely change the default

value to a different value or data type, as long as they are unique to this collection and not an array

data type.

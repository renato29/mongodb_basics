# What is MongoDB?

MongoDB is a popular database platform for storing information for web applications. According to [its website](#https://www.mongodb.com/), MongoDB "is a general purpose, document-based, distributed database built for modern application developers and for the cloud era."

A database is an organized collection of digital data stored on a computer. In the physical world, a database is like a file cabinet or warehouse, and the information is like the folders, papers, or other things inside. Instead of a file cabinet or a wharehouse building, however, the database is located on a computer.

Like a file cabinet or warehouse needs workers who know how to find and maintain the things stored within, a database needs software for managing. Not only does MongoDB store the data, it also is the software you need to interact with the data. Like with many databases, with MongoDB you can interact in powerful ways with information stored within. For instance, you can search, reference, compare, change  otherwise manipulate the stored information. You can do so with optimal speed and minimal processing expense.

You can work locally on your computer with MongoDB, but they also offers cloud-based services. Using their cloud services, you can access your database so long as you have internet access. You will focus on using the cloud-based service called [Atlas](#https://docs.atlas.mongodb.com/). From their website, "MongoDB Atlas is a fully-managed cloud database."

'''''''
MongoDB is cross-platform, meaning you can use MongoDB with many different programming languages, like NodeJS, Python, and others. 

Unlike SQL databases where you store information in tables, MongoDB is known as NoSQL because it doesn't store information in tables. Rather, it stores information in documents. In MongoDB, each database can have multiple collections of documents. You can fill each collection with whatever information you want, but typically a collection is made up of documents containing the same or similar information. For instance, a collection for all your users. Or a collection for all the purchases made from your e-commerce store. Or a collection for all comments made on your blog. 

The documents are JSON-like, which makes them flexible to work with. One of the main JSON-like features is that the structure of each document in a collection does not have to be identical to the structure of the other documents in that collection. For instance, in your users collection, some users may have a first name, last name, birthday, and user_id. However, not all users are required to have all fields. It's okay of some users are missing one or more of first name, last name, birthday, and user_id

 
## [Setting up MongoDB Atlas](#setting-up-MongoDB-Atlas)
https://docs.atlas.mongodb.com/getting-started/
Part 1: Create an Atlas Account.

## [Deploy First Cluster](#deploy-First-Cluster)
Part 2: Deploy a Free Tier Cluster.

## [Connect IP Addresses](#connect-IP-Addresses)
Part 3: Add Your Connection IP Address to Your IP Access List.

## [Create Database](#create-Database)
Part 4: Create a Database User for Your Cluster.

## [Connect to Cluster](#connect-to-Cluster)
Part 5: Connect to Your Cluster.

## [Add Data To Database](#add-Data-To-Database)
Part 6: Insert and View Data in Your Cluster.
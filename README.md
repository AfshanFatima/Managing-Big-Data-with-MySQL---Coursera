# [Managing Big Data with MySQL](https://www.coursera.org/learn/analytics-mysql)

  Duke University

**About this Course**
This course is an introduction to how to use relational databases in business analysis.  You will learn how relational databases work, and how to use entity-relationship diagrams to display the structure of the data held within them.  This knowledge will help you understand how data needs to be collected in business contexts, and help you identify features you want to consider if you are involved in implementing new data collection efforts.  You will also learn how to execute the most useful query and table aggregation statements for business analysts, and practice using them with real databases. No more waiting 48 hours for someone else in the company to provide data to you – you will be able to get the data by yourself!

By the end of this course, you will have a clear understanding of how relational databases work, and have a portfolio of queries you can show potential employers. Businesses are collecting increasing amounts of information with the hope that data will yield novel insights into how to improve businesses. Analysts that understand how to access this data – this means you! – will have a strong competitive advantage in this data-smitten business world.

 Show less

**SQL Glossaries**

Here are some useful SQL and ERD links that might be helpful in this course.

http://www.sqlcommands.net/

https://www.codecademy.com/articles/sql-commands?r=master

http://www.tutorialspoint.com/sql/ (use table of contents on left)

http://www.w3schools.com/sql/

http://cse.unl.edu/~sscott/ShowFiles/SQL/CheatSheet/SQLCheatSheet.html

http://dev.mysql.com/doc/refman/5.7/en/

**Syntax Error Checklist**

There are several common errors that learner's make when writing their queries. If you are experiencing a syntax error, please use the checklist below to help identify the error and make the necessary changes to your query. If the checklist items are all correct in your query, please use the forums to see if one of your peers can help.

When posting to the forums, it is important to post in the correct week and to add a screen shot of your query. Without that, it is difficult to provide guidance on what changes should be made.

Syntax Error Checklist:

When reviewing your queries for errors check the following:

* All keywords are spelled correctly
* All keywords are in the correct order
* Aliases do not have keywords or reserved words in them. You can use these websites to lookup whether your alias is a keyword or a reserved word:

http://hsqldb.org/doc/guide/lists-app.html

https://www.petefreitag.com/tools/sql_reserved_words_checker/

http://tunweb.teradata.ws/tunstudent/reservedwords.htm

* Aliases and title names do not contain white spaces (unless the full     title is encased in quotation marks)
* Quotation marks are of the correct type
* Semi-colons are at the end of your query, not in the middle
* All opening parentheses are matched with a closing parentheses
* There are commas between all the items in a list- there is NOT a comma   after the last item in a list
* All text strings are enclosed with the appropriate types of quotation     marks
* Each column name is linked with the correct table name
* All the necessary join conditions are included for each join

**Guidance for writing queries**

Learning how to write queries takes time and practice, and writing valid queries is a critical skill in working with databases. Below are some suggestions about working with queries, including a syntax error checklist of common problems.

**Complicated Queries:**

Click the document below for guidance on writing complicated queries.

Working through complicated queries.pdf

# Additional SQL Resources

Resources and notes provided by Dr. Jana Schaich Borg, Duke University

Many of you have asked for recommendations of other SQL books or resources you could use to continue practicing SQL. Below, I have provided some resources that I found to be particularly helpful.

**Books**

* SQL in 10 Minutes, Sams Teach Yourself by Ben Forta https://www.amazon.com/SQL-Minutes-Sams-Teach-Yourself/dp/0672336073
This book will review all the information you learned in this course, and provide some extra information about the commands one uses to create a database. I find the writing to be very clear and concise.

* SQL Database for Beginners by Martin Holzke with Tom Stachowitz https://www.amazon.com/SQL-Database-Beginners-Martin-Holzke/dp/099040207X/ref=sr_1_1?s=books&ie=UTF8&qid=1470318766&sr=1-1&keywords=SQL+Database+for+Beginners

This book is also very clearly written, but provides much more background and detail than “SQL in 10 minutes.”

* MySQL Cookbook by Paul DuBois https://www.amazon.com/MySQL-Cookbook-Solutions-Developers-Administrators/dp/1449374026/ref=cm_cr_arp_d_product_top?ie=UTF8
This is a book for intermediate to advanced users, because it assumes a lot of working knowledge of SQL and often doesn’t explain the logic behind the solutions in provides. That said, it provides very useful “recipes” for how to solve common problems you might encounter, which has saved me time on multiple occasions.

* Database Systems: Introduction to Databases and Data Warehouses by Nenad Jukić, Susan Vrbsky, and Svetlozar Nestorov. https://www.amazon.com/Database-Systems-Introduction-Databases-Warehouses/dp/0132575671/ref=sr_1_1?s=books&ie=UTF8&qid=1470319426&sr=1-1&keywords=Database+Systems%3A+Introduction+to+Databases+and+Data+Warehouses

This is the textbook I referenced in the first weeks of the course. It is more expensive than the other books I’ve listed, but I still find it to be one of the most accessible descriptions I’ve read of how to design databases. I know that Dr. Jukić and his co-authors are working on ways to reduce the cost of the book, so keep an eye out for price drops, and consider buying a used version!

**Practice More SQL**

When I was learning SQL, I found it difficult to find one set of resources that would allow me to learn SQL efficiently and holistically. Further, I lost a lot of time troubleshooting my own desktop version of MySQL. I designed this course the way I did to prevent other people from having to go through the same frustration I did cobbling together a comprehensive learning experience. At present, I do not know of any other freely-available resource that allows students to practice SQL the way you have been able to in this course. Of course, new resources are popping up every day, so please let me know if there are any helpful websites I should make other students aware of!

In the meantime, here are at least two ways you can practice more SQL queries.

Download your own version of MySQL to your desktop http://dev.mysql.com/doc/refman/5.7/en/installing.html and either make your own database (using commands you can find online, but that we did not review in this course), or download a free one. There are many free SQL databases available online, but here are a couple websites to get you started:

http://dev.mysql.com/doc/index-other.html (see the “example databases” heading

http://sportsdb.org/sd/samples

http://www.eclipse.org/birt/documentation/sample-database.php

https://chinookdatabase.codeplex.com

2. Monitor forums like this one to see other people’s suggestion of online resources they find helpful:

https://www.quora.com/Is-there-a-site-for-online-SQL-practice

**You can download this information as both a Word Document and a PDF. You must have Adobe Acrobat Reader to download any PDF file.

Microsoft Word_Additional SQL Resources.docx

PDF_Additional SQL Resources.pdf

# Jupyter Basics

Jupyter instructions are also available in these two videos: How to Use Jupyter Notebooks and How to Use Your Jupyter Account. Check them out if you have not.

If your Jupyter account is going to expire before you complete the course or the specialization, please follow these instructions to reset the account.

Jupyter is an online interface that allows you to practice MySQL queries online, without having to download, install and configure MySQL and a database on your own computer. Each learner will have her or his own private Jupyter folder containing files called "notebooks," each of which includes a series of exercises in which you can practice various features of MySQL. The notebooks all allow you to connect to the Dognition database described earlier, so when you run queries in your Jupyter notebooks, you will be querying that database.

To access a Jupyter notebook, click on one of the MySQL exercise items in this course, such as "Jupyter Exercise 1: Looking at Your Data," then click the "Open Tool" button to be taken to that notebook. The notebook is housed on a server outside of Coursera, at Duke University. 

A Jupyter notebook includes instructional information (written-out information about MySQL and how to write MySQL queries) and query boxes (in which you can type and run MySQL queries to practice what is taught in the written materials). For these instructions, we will use Exercise 1 as an example. 

Here is a screen shot of one portion of Exercise 1 notebook, with the text block instructional information and query boxes highlighted. 



To use the notebook, carefully read the text information and follow the instructions to create and run queries, to learn the various MySQL functions being taught in the course. There are 12 notebooks with progressively harder content - by the time you have completed all of them you will be proficient in MySQL!

When you run a query, the output of the query will appear immediately below the query box in which you typed the query. If you receive an error message because you wrote the query incorrectly, you may want to clear the error and try again. You may also want to clear the correct output and try again. To clear the output of a query, place your mouse cursor in the query box of which you want to clear the output, and choose Cell > Current Output > Clear. Then, adjust your query and re-run it. 

You can save the notebook as you work by choosing File > Save and Checkpoint periodically. When you return to the notebook, you will return to the last saved version, and you can also return to any specific "checkpoint" version by choosing File > Revert to Checkpoint and then select the date/time to which you wish to revert. 

Working in the Jupyter home page

Each Jupyter exercise is a "notebook" file, as mentioned. There are 12 notebooks in this course, and if you go to the home page of your Jupyter account you can see all of them. To go to your Jupyter home page, click the word "Jupyter" at the top left of any notebook or click on the link to your home page provided in Lesson 2 of Week 2. A new window will open and you will see a list of files like this:



If any of your notebooks are currently running, their icon will be green and the word "Running" will appear to the right. When you are done with a notebook it's always best to shut it down. To do so you can select it from this list by clicking the checkbox to the left of the notebook, and click "Shutdown" at the top ("Shutdown" appears as an option when any of the notebooks are selected).



To open any notebook, click it from this list. 

You can duplicate, rename or delete any notebook by selecting the checkbox to the left of its title, then clicking the appropriate menu item at the top of the page. Duplicating or renaming your notebooks is something you might want to do if you want to keep clean copies of notebooks before you begin working on them. 

Notice the notebook titled "restore-my-notebook.ipnyb." This notebook contains instructions for how to re-install clean copies of all 12 of the course notebooks into your Jupyter home directory. This is something useful to do if you accidentally delete one or more of your notebooks, or alter them significantly and wish to recover clean, new versions of each notebook. However, restoring will OVERWRITE all of the existing notebooks with new versions of each (any work you had saved in the notebook would be lost, if you did not save the notebook with a different name BEFORE restoring).

IMPORTANT INFORMATION ABOUT YOUR JUPYTER ACCOUNT



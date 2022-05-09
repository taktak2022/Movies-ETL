# Movies-ETL

## Overview
This assignment was to create a Database in pgAdmin using PostgreSQL and Jupyter Notebook through the process of ETL: Extract Transform and Load.  The data for this process was movie metadata datasets from Kaggle in the forms of CSV files and Wikipedia JSON files as well as ratings data from MovieLens.  NOTE: Due to the sizes of these files, which were extremely large, pushing them into this repository was not possible (not allowed by GitHub).
![module 8 3 5 git push error](https://user-images.githubusercontent.com/99851509/167495820-7f10d7a7-470e-4e99-b48a-3d0142ff56bb.png)


The data was then parsed, cleaned and organized with Python and Jupyter Notebook to be presented for a large company's hacking competition or "Hack-A-thon".  Once the data was transformed, it was then loaded to pgAdmin using SQL.

The assignment proved to be very difficult in the way it was presented.  The starter code for the Challenge was not broken up by individual cells but bunched together in one large cell's code block, which in my opinion defeated the purpose of utilizing the benefits of Jupyter Notebook's error solving capabilities.  With Deliverable 2, I personally contacted 5 different BCS Learning Assistants, because the first 4 could not assist me in explaining and correcting the many errors that kept showing up as a result of the way the starter code was written up - very poorly.  I faced NameErrors, TypeErrors, AttributeErrors and a few more that I have never seen before.

This assignment should have been explored more in-depth so, as a student, we can get a stronger foundation to further our knowledge of all the things to come.  

Once the ETL process had been completed, the wiki_movies Dataframe looked like the following:
![image](https://user-images.githubusercontent.com/99851509/167494583-3d56542c-dd13-462c-9f29-3ac68dcacfd1.png)

The Kaggle metadata:
![image](https://user-images.githubusercontent.com/99851509/167495131-ceaaf3e3-9c83-425e-85e3-56543f9b9fae.png)

And the MovieLens ratings data:
![image](https://user-images.githubusercontent.com/99851509/167495496-15a61f77-d54c-4439-970f-7aed10ea3e6e.png)

Also the screenshots of the queries after the data had been loaded to the database from pgAdmin:
![movies_query](https://user-images.githubusercontent.com/99851509/167496106-e2b59a2e-efa9-465a-9076-f8750efb16ab.png)
![ratings_query](https://user-images.githubusercontent.com/99851509/167496133-a5af780b-0aef-45bd-8cb8-f78bcff46de8.png)

## Summary
As of this writing my assignment has yet to be graded so I am unsure if I succeeded in achieving the goals of this assignment.  I can honestly say, I do not completely understand it.  I would say about I am about 65% confident I could figure it out if I have to re-submit it.  That being said, I did learn a few things along the way.  Mostly from the Learning Assistants who happen to agree with me that the way this Challenge's starter code was badly written up.  The fact that it took so many learned people in this field to figure out the errors says something...and that was after two days of struggling by myself to figure out what and/or why the code was not working.  I hope there comes a day when I do understand this process in full.

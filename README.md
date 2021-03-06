# Week 7 - Python Scripts

## Outline

* Go over some homework 2 questions
* AWS Educate by Felix. [Slide Deck](https://docs.google.com/presentation/d/1L1HcyrfJf0JEf6POj8y5fRks3Ugt0szD7M-ceeC6bio/edit?usp=sharing)
* Demo pgAdmin 4 dashboard
* Wrap up questions as functions / Execute use cases with the technologies we've been exposed to so far.
  * What's the closest bike station to my current position?
    * Imagine that your phone gives the lat/lng. We'll add a geocoding API soon.
  * How many Covid cases in my neighborhood?

## Homework

* [Homework 3](https://canvas.upenn.edu/courses/1533813/assignments/8421896?module_item_id=19270424) is due Oct 22nd
* Install [pgAdmin 4](https://www.pgadmin.org/download/) and setup class server for access. Use the [class credentials here](https://canvas.upenn.edu/files/89654914/download?download_frd=1) and follow this [AWS guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToPostgreSQLInstance.html). You won't need to look at AWS RDS console as you have all the credentials needed in the JSON file.
* Read about SQL Injections
  * [Python practical walk through](https://realpython.com/prevent-python-sql-injection/)
* Listen to Paul Ramsey talk about PostGIS in a podcast from last month: <https://open.spotify.com/episode/5z9MbiMLOwAL1xO6WGbN6g?si=6KLb9ffGT9WzJlNfbxIDpw>

### Lecture

1. Review Homework 2
2. Felix gives little presentation on AWS
3. Putting the pieces together with Python?
  * Getting data from the full OSM database via BigQuery


#### Follow Along

1. `conda deactivate` to make sure you don't have an env activated
2. `conda activate musa509week6` -- to activate the environment from last week
3. `jupyter lab`


### Lab

1. Writing and running Python scripts
2. View AWS RDS PostgreSQL/PostGIS instance via pgAdmin4

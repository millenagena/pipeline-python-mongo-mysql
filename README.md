# pipeline-python-mongo-mysql

In this project, a data pipeline was developed following the workflow below:

![image](https://github.com/millenagena/pipeline-python-mongo-mysql/assets/69437878/cc958bc5-b147-4d1d-9aea-78a69602aa7d)

In the notebook `extract_and_save_data.ipynb`, I start by extracting data from an API that contains information on sold products. Once the data is extracted, I store it in a MongoDB Atlas database.

Next, in the `transform_data.ipynb` notebook, I retrieve the data from the MongoDB database and apply various transformations. Once transformed, the data is saved in CSV files.

In the final notebook, `save_data_mysql.ipynb`, I use `mysql.connector` to establish a connection between Python and the MySQL Server on my local machine. Once connected, I create a database and a table to house the transformed data.

Additionally, in the scripts folder, you'll find several Python scripts where I've transformed the codes developed in these notebooks into Python functions.

This project was developed for a course I taught at Alura. As soon as the course is ready, I will make the link available here.

## Technologies used

* Python;
* MongoDB Atlas;
* MySQL;
* Pymongo;
* MySQL Connector/Python.

## Contact

Email: millenagena@gmail.com

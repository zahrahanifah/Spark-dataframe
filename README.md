# Processing Big Data with Spark

### The Goal is : 
To extract data from csv file to dataframe, filter it with multiple condition, and convert it into JSON and parquet file.

### The Challange is : 
The csv file is quite big, hence we use Spark for this repo

### File used on this repo :
1. `fhv_tripdata_2019-01.csv` : is the csv file
2. `spark.ipynb` :  python file (or jupyter notebook) to import file from csv file and filter the dataframe with multiple condition

### The process :
Simply just run the `spark.ipynb` then it will generate `output.JSON` and `output.parquet` 
(Do not forget to change the input and output path to your local)
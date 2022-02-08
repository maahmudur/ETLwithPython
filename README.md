# ETL with Python
Example notebooks to demonstrate ETL (Extraction, Transform and Load) process using Python.
</br>
## Using Pandas

* Source Data:<br>
We will use a salary data collected from a ready made garments factory.

* Extraction:<br>
Data will be extraced from the raw excel format provided by the factory.

* Transformation:<br>
Python's pandas library will be used to clean and harmonize the dataset.

* Loading:<br>
Final dataset will be uploaded to a MySQL database.

Here is the 
[notebook](https://github.com/maahmudur/ETLwithPython/blob/fd7e0343c5a1e0afb3e8832d75c5ee5d717b8c9a/ETL_using_Pandas.ipynb).


## Using PETL

* Source Data:<br>
Bank of Canada's Exchange Rate and a local Expense file.

* Extraction:<br>
Bank of Canada's exchange rate will be extracked from their API using 'Requests' python module in JSON format and the local expense file which is in Excel format will be read into PETL table.

* Transformation:<br>
PETL will be used to merge and clean two datasets into the final one.

* Loading:<br>
Final dataset will be uploaded to a MySQL database.

Here is the
[notebook](https://github.com/maahmudur/ETLwithPython/blob/fd7e0343c5a1e0afb3e8832d75c5ee5d717b8c9a/ETL_using_PETL.ipynb).
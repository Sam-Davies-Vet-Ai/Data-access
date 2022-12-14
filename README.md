# Big Query access using a service account key


## Description
This script will allow create a connection in python to bigquery. There are 2 scripts within this repository

* BQ_Access.ipynb - will list all datasets, tables and give a snapshot of the first 5 rows of each table
* BQ_Single_Table_Example.ipynb – will return all the rows from to 1 table to a dataframe and then print the dataframe

These scripts need to be used with a json file containing the details of a service account key, the data returned will be limited to the access granted to the service account key

These are example scripts to access data, these can be used as a base to develop scripts to perform the function you require

## Usage

* Open the file you wish to run e.g BQ_Access.ipynb
* Select 'Open in Colab'
* This will create a new Colab instance
* Any changes you make will not be saved to github
* Select the folder icon on the left-hand side of the screen in Colab
* Drag and drop the json service account key into this area
* This uploads the file to the Colab sessions storage
* change the xxxxx.json to the name of the file uploaded inclusive of the .json
* Select 'Runtime' in the top menu bar and 'Run all'
* This will run the script and give you the desired formatted output

##
<p align="right">
<img src="https://github.com/Sam-Davies-Vet-Ai/Data-access/blob/main/vet-ai-white.png" width="100"/>
</p>


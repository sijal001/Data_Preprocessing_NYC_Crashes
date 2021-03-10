# nyc-crashes

---


- Repository: `nyc-crashes`
- Type of Challenge: `Consolidation`
- Duration: `2 days`
- Deadline: `10/03/2021 05:00 PM`
- Deployment strategy :
  - Github page
- Team challenge : `solo`

## Mission objectives

- Be able to use pandas
- Be able to clean a data set
- Be able to do prepare a data set for a machine learning model

## The Mission

Bill de Blasio, mayor of New York City, is in a bit of a pickle. Indeed, his police department, the NYPD, collected information about all the traffic accidents that happened in New York City. 
However, they are too busy eating doughnuts to correctly encode each traffic indicent, and so it happens that the dataset that we got here is quite dirty, has a lot of missing values and can't be used by a machine learning model as is.

What he wants exactly is to predict which streets are the most dangerous while visiting the [city that never sleeps](https://en.wikipedia.org/wiki/The_City_That_Never_Sleeps).

# About Running the Program

* **Python version:** `3.8.5`

**Imporant Libaries:**

| Library       | Used to                                        |
| ------------- | :----------------------------------------------|
| folium	|to manipulate data then visualize it in a map   |
| geopy		|to get the longtitude and latitude of a address |
| numpy		|to work around multi-dimensional of generic data|
| os		|to work around system path.			 |
| pandas        |to manupulate the data.			 |
| sodapy        |to downloading the data set			 |
| seaborn       |to to have beautifyl visualization 		 |

**Note:** Just use command below to install the required libary with correct version to run the program smoothly.

"pip install -r requiement.txt"

# Architecture

```
3D-House-Project
│   README.md               :explains the project
│   requirements.txt        :packages to install to run the program
│   
│   download.ipynb  	    :script to download a differently sized dataset.
│   3d_house.ipynb          :script to run in order to start the program
│   
│   data_files 		    :directory contains all maintainted .csv files.

```

---
# Instruction
#### How to get 3d_location ploting

1. Setup python environment  `3.8.0`
2. Install all libaries `pip install -r requirements.txt`
3. Download important "data_10000.csv" files `download.ipynb` or just use sample data set provided.
4. Run the `main.ipynb` in jupyter notebook
5. Run all code
6. Have a look on the statistics genereted.

---
# Next Step

1. Get null value of latitude and longitude using zip_code
2. Futher Filter the data.


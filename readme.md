![Pharmaceutical Data Analysis](images/header.jpg)

## The project consists of analyzing data about test results of a new cancer drug on mice by a pharmaceutical company. 

# **Overview**

- The analysis will be done using pandas jupyter notebook
- Python libraries used: pandas, matplotlib, scipy
- Calculations, summary and insights are contained in [pymaceuticals_starter.ipynb](pymaceuticals_starter.ipynb)

# **Repository Structure**

```` bash
│   .gitignore                              # GITignore file
│   changelog.md                            # Contains commit history
│   LICENSE                                 # License for the repo
│   pymaceuticals_starter.ipynb             # MAIN file for the app
│   readme.md                               # ReadMe file
│
├───data                                    # Raw data for analysis      
│       Mouse_metadata.csv                  # Mouse test subjects data
│       Study_results.csv                   # Study results data
│
└───images                                  # Images for readme formatting
        header.jpg                          # Header image
        sc1.png                             # App screenshot
        sc2.png                             # App screenshot
        sc3.png                             # App screenshot
        sc4.png                             # App screenshot
        sc5.png                             # App screenshot

````

# **Application breakdown**

- The application imports the two csv files provided [Mouse_metadata.csv](data/Mouse_metadata.csv) and [Study_results.csv](data/Study_results.csv)
- The application annotates the mouse metadata in each observation by merging the two files into a single dataframe

<p align="center">
  <img src="images\sc1.png">
</p>

- Next, the application checks for duplicated data and prints out if any duplicates are found
- If duplicated values are found it deletes them
- After cleaning the data, it is time to begin the proper analysis, the first analysis is a summary stats dataframe
- For practice purposes the summary stats are obtained using 2 methods:
    - The first method involves groupby and data manipulation on an operation by line approach. Easier to review and troubleshoot the logic

  <p align="center">
  <img src="images\sc2.png">
  </p>

    - The second method does all calculations on a single line of code, harder to review and troubleshoot but extremely effective

  <p align="center">
  <img src="images\sc3.png">
  </p>

    - Both methods are consistent and produce exactly the same results

<p align="center">
<img src="images\sc4.png">
</p>

- After that the application analyzes the data and produces a variety of graphs used in order to obtain some insights for the data provided, the insights are contained in the [pymaceuticals_starter.ipynb](pymaceuticals_starter.ipynb) jupyter notebook

<p align="center">
<img src="images\sc5.png">
</p>


# Test task for the company "Ulybka Radugi" (Data Analyst position)


***STATUS:*** **Completed**


## Project Goals:

The task involves completing a test assignment, including creating five SQL queries based on the available data. Solving the problem of evaluating the results of an A/B test. Cleaning the dataset from outliers.

## Tasks:

### SQL 1:

Given 4 columns: Store, City, Product Code, Product Direction

Condition:
It is necessary to obtain all possible store-product combinations (without using the SALES table)

#### SQL 1 Task Execution Result:

<img src="https://i.imgur.com/NacBKXS.png" alt="SQL1"/>

### SQL 2:

Given 5 columns: Store, City, Address, Quantity in pieces, Amount in rubles

Condition:
It is necessary to obtain all possible store-product combinations (without using the SALES table)

#### SQL 2 Task Execution Result:

<img src="https://i.imgur.com/6mVHGYg.png" alt="SQL2"/>

### SQL 3:

Given 3 columns: Date, City, Share in total sales in rubles by date

Condition:
Select only for products in the CLEANING category

#### SQL 3 Task Execution Result:

<img src="https://i.imgur.com/9vs5IQv.png" alt="SQL3"/>

### SQL 4:

Given 3 columns: Date, Store, Product

Condition:
Information about the top 3 products by sales in pieces in each store on each date

#### SQL 4 Task Execution Result:

<img src="https://i.imgur.com/n5WKzWL.png" alt="SQL4"/>

### SQL 5:

Given 4 columns: Date, Store, Product Direction, Amount in rubles for the previous date

Condition:
Only stores in St. Petersburg

#### SQL 5 Task Execution Result:

<img src="https://i.imgur.com/fyKpfXO.png" alt="SQL5"/>

### A/B Test Results Evaluation Task:

Given:

A selection of customers (17,744) was made, who have their birthdays soon, to send them a congratulatory SMS mailing and notify them of a personal discount.
The obtained sample was randomly divided into target (received the mailing) and control groups in a ratio of 75% to 25%.
The promotion lasted for 3 days.
Below is the data on the number of responding customers in each group during the promotion period. It is also known that the delivery rate of messages for this mailing was only 2/3 of the total mailing volume.

Required:

Calculate the number of additionally attracted customers due to the mailing. Save the formulas in a file.

#### Task Execution Result:

<img src="https://i.imgur.com/3oORjch.png" alt="Excel"/>

he complete solution with formulas is available in the Excel file in this repository.

### Task for Outlier Data Cleaning:

Given:

On the "Data for Cleaning" sheet, daily sales in pieces for one store for the period from January 2020 to May 2022 are provided. Sales dynamics show both stable patterns and anomalous values.

Required:

Identify outliers in the data, replace them, taking into account the detected patterns. Save the formulas in a file. In case of using R/Python programming languages for the solution, attach a script with all data processing steps.

#### Task Execution Result:

Visualization of initial data:

<img src="https://i.imgur.com/FoBNZkd.png" alt="vid1"/>

Visualization of data after outlier processing:

<img src="https://i.imgur.com/nEl9yj9.png" alt="vid2"/>

Outlier processing in this task seemed unsatisfactory to the employer. Analyzing the shortcomings, it was decided to seek help from a neural network that identified all outliers based on the LSTM Autoencoder outlier detection algorithm.

Here is its result:

<img src="https://i.imgur.com/Nz8Kv0n.png" alt="vid3"/>

View of the dataset after replacing all outliers, taking into account the detected patterns:

<img src="https://i.imgur.com/61aPxrv.png" alt="vid4"/>

---

<img src="https://i.imgur.com/CxBDSVg.png" alt="vid5"/>

The code with explanations is available within this repository.

## Project Tools

- Python
- Pandas
- Sklearn
- Matplotlib.pyplot
- Keras
- SQLite3

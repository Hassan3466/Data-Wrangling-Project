# Data-Wrangling-Project
## Introduction
The objective of this project is to wrangle, clean, and generate insight from Twitter data 
knowns as WeRateDogs which their focus is based on rating dogs and categorizing them. 
To complete what is being taught in class and to have a better understanding of the 
wrangling and cleaning lesson in the Nanodegree program, this project was given out as an 
assignment. Data was collated from different sources csv, tsv, and twitter itself. Wrangling 
was done with the use of python libraries, and finally visualization was obtained.

Gathering Data
As reported earlier in the introduction aspect of this report, data were sourced from three 
different location. The first one was provided in a CSV file which was given by Udacity and 
was read using the function pd.read_csv 
The second one which is the image_prediction.tsv file which was hosted on Udacity’s server 
and was downloaded using the python requests library. The image below shows how the 
data was sourced.
The third data was obtained from Twitter with the aid of Twitter API and Tweet JSON file. 
This data was generated to serve as an additional data to the previous ones. During the 
process of obtaining the data new columns that was needed was generated which are 
favorite_count and retweet_count querying.

Assessing
The data were assessed using two methods
1. Data quality issues: This is to check for missing values, duplicates, and incorrect 
values in the data frame.
2. Tidiness issues: This are structural issues in the data frame.
Both were done using the visual assessment which was done using spreadsheet and 
notebook while on the other hand the programmatic assessment was done using some 
specific pandas’ functions to have an overview of the data structure. Immediately after 
assessing the data and it has been cleaned it was then declared ready for the descriptive 
analysis. The three data set were merge into a single data using the panda’s function”. 
merge ()” and the saved as a csv file. Meaningful information was generated during the 
descriptive analysis phase.

Descriptive Analysis and Visualization 
After finishing with the cleaning of the data frame, insight and visualizations were 
generated to have an overview and a clearer picture of the datasets. Different columns 
were combined to have meaningful visualization.

# DAT-ATX-1_Project
## Austin Restaurants Health Inspection

General Assembly -  Data Science Course capstone project

#### Preliminaries - Goal of this project

The Austin/Travis County Health and Human Services Department conducts the permitting and inspection of more than 4,000 food establishments in Austin, several local municipalities and rural Travis County. Food establishments should be inspected twice a year. If unable to be inspected at this frequency, then inspections are prioritized by risk. The establishments include a wide variety of food industries, such as restaurants, delicatessens, school cafeterias, grocery stores, retail meat markets, bakeries and bars. If no violations are found, a score of 100 is achieved. If more than 30 points are lost, a re-inspection is required and corrections must be made to bring the score above 70, in accordance with the Texas Food Establishment Rules. If subsequent inspections score below 70, compliance actions will be taken.

In our analysis we will follow a scheme similar to the one in place by the New York City Health Department; To help the public understand the results of these inspections, a grade of ‘A’, ‘B’, or ‘C’ is assigned ad hoc for the purposes of this Data Science project to each restaurant based upon the inspector’s score, with A (Scores between 90 and 100) being the best grade. Even though Austin restaurants do not follow a letter grading scheme which would require them to post their grades at the restaurant’s entrance, so potential patrons can have insight into the restaurant’s health standards, the Austin/Travis County Health and Human Services Department provide a website where searching for a specific restaurant's health inspection scores history is easily attainable.

Since restaurants in Austin are not required to publicly display their health inspection results, potential patrons are left to guess what the health inspection score would be. The potential patron would, however, know various facts about the restaurant, such as restaurant name, type of food, street address, neighborhood, and zip code. The goal of this project is threefold: 

- To explore the data set and come up with interesting patterns and visuals
- To create predictive models about a restaurant's health inspection score given the basic facts mentioned above. Both regression and classification **supervised learning** techniques will be implemented.
- To study the data set as a whole, ignoring the health inspection scores. Are there any discernible patterns in the data (Restaurants' names, street addresses etc) - this will be done with **unsupervised learning** techniques.

#### Dataset

The main dataset we will be using is provided by the [City of Austin's Data Portal](https://data.austintexas.gov). The City of Austin publicly posts the results of their restaurant inspections in an online database, and makes them downloadable as text files. These text files contain information on every inspection the city has performed, and includes the inspected restaurant’s name, address, zip code, inspection date, inspection score and the process description (whether it is a routine inspection or a follow-up). Unfortunately the information provided by the City in this data set leaves a lot to be desired; Compare for example the information provided by the city of New York: restaurant’s name, address, zip code,
borough, food type, inspection date, health violations found, inspection score, health grade, and any punitive actions taken by the health department. Such a rich data set definitely provides with way more opportunities for further analysis.

To make the information useable, the csv files are loaded into pandas for further processing within Jupyter Notebooks. Further information will be provided within the Notebooks.


# Title : Tanzania ministry of water Predictive Modelling: Predicting Functionality of water pumps in Tanzania

**Authors**: Cynthia Adisa


![well](https://github.com/khasoha/Phase3_project/assets/103565165/7477bff0-f8f9-40cd-a0bc-1b1645caef50)

## Overview
Tanzania, as a developing country, struggles with providing clean water to its population of over 57,000,000. There are many water points already established in the country, but some are in need of repair while others have failed altogether.


## Business Problem

Tanzania Ministry of water needs to identify which pumps are functional, which need some repairs, and which don't work at all that will influence their decision to either get new pumpsor repair the ones existing.
They also need to develop a model to identify and improve on maintenance operations of the pumps.


## Data

The dataset contains the following is a set of information about the waterpoints:

*amount_tsh - Total static head (amount water available to waterpoint)

*date_recorded - The date the row was entered

*funder - Who funded the well

*gps_height - Altitude of the well

*installer - Organization that installed the well

*longitude - GPS coordinate

*latitude - GPS coordinate

*wpt_name - Name of the waterpoint if there is one

*num_private -

*basin - Geographic water basin

*subvillage - Geographic location

*region - Geographic location

*region_code - Geographic location (coded)

*district_code - Geographic location (coded)

*lga - Geographic location

*ward - Geographic location

*population - Population around the well

*public_meeting - True/False

*recorded_by - Group entering this row of data

*scheme_management - Who operates the waterpoint

*scheme_name - Who operates the waterpoint

*permit - If the waterpoint is permitted

*construction_year - Year the waterpoint was constructed

*extraction_type - The kind of extraction the waterpoint uses

*extraction_type_group - The kind of extraction the waterpoint uses

*extraction_type_class - The kind of extraction the waterpoint uses

*management - How the waterpoint is managed

*management_group - How the waterpoint is managed

*payment - What the water costs

*payment_type - What the water costs

*water_quality - The quality of the water

*quality_group - The quality of the water

*quantity - The quantity of water

*quantity_group - The quantity of water

*source - The source of the water

*source_type - The source of the water

*source_class - The source of the water

*waterpoint_type - The kind of waterpoint

*waterpoint_type_group - The kind of waterpoint


## Methods

I was able to do a train test split in the models: Random forest classifier, linear regression and K-Nearest neighbors models optimized by one Hot encoding and  scaling.

For the dataset provided I was The method adopted was the KNN model as it produced the most favorable predictive results of the three models with an accuracy of 66%.



## Results

Factors such as type of water, i.e soft,salty,milky etc. seem to affect the performance of the pumps long term.Same to the sourse of water as we see the spring water wells are the msot functional.The make of the wells also affects the performance as communal sandpipes and hanpiped pumps perform best.


## Conclusions

1.)The Tanzania water ministry should consider investing more in areas with soft water as opposed the other water types i.e. salty, milky, fluoride seem to be affecting the lifespan of the pumps.

2.)The ministsry should also focus on drawing water from springs 

3.) They can also invest more on communal sandpipes and hanpiped pumps as they are the most functional



## For More Information

For any additional questions, please contact **Name: Cynthia Adisa   email:Cynthia.adisa@student.moringa.com **

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── 8867.Microsoft_5F00_Logo_2D00_for_2D00_screen-1920x706.jpg
├── Microsoft Movie Studio Needs Analysis presentation.pdf
├── README                         
├── __init__.py
├── image.png                                                  
├── phase_1_project.ipynb
        


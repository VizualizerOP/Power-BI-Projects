# Power-BI-Projects

The Dataset used in my project is the Zomato where i have created an interactive dashboard after cleaning and transforming data.
Following is the case study of Zomato

PROJECT DESCRIPTION

High Level Business Requirement

Zomato is a restaurant search and discovery service. Operating in several countries worldwide, 
they provide detailed information and customer reviews of various restaurants. The owners of 
Zomato, want to unearth the hidden anomalies in their business data. The final objective is to 
analyze the data in a way which helps them to accurately judge their business performance.
The data (sample) is currently available in the form of a few excel files with each file containing 
information about several restaurants operating in a specific continent. The clients want to create 
a consolidated and interactive PowerBI report from where they can easily analyze the following 
information:
1) Total number of restaurants across continents, countries and cities.
2) The ability to view information at a global level. But at the same time, the ability to go down 
to a granular level as well.
3) Top performing restaurants by average customer ratings.
4) Top performing restaurants by least average cost.
5) Ability to filter and view the restaurant details (address, cuisines served …) on the basis of:
a. Geographic dimensions like continent, country and city.
b. If the restaurant offers services like, online delivery or table booking.
c. Rating colors denoting the average rating slab.
6) Top ranking restaurants by the number of cuisines they serve.

Step 1: Data Import 

The files that were imported are as follows:-
1. Africa
2. Asia
3. Country-Code
4. Europe
5. NAM
6. SAM
7. Oceania
8. Fact Table

Step 2: Data Transformations 

In this some of the city words like Sí£o Paulo and ÛÁstanbul have changed to São Paulo and Istanbul. Also Cedar Rapids/Iowa City has been changed to Cedar Rapids.The columns were created to show the restaurant address and restaurant name. Some columns were not relevant so that had to be removed that were duplicated and was no use.

Step 3: Data Modeling 

In this the cardinality and cross filter direction was set so that the aggregations can happen accurately at the report level. Other data manuplations were made like:-
1) There is a list of geographic columns. Go through the list and categorize them appropriately.
2) Create a user-defined hierarchy and include all the geographical dimensions in there.
3) Group the countries into appropriate continents.

Step 4: Use of DAX Functions

DAX functions were created for the following 

Using DAX
1. There needs to be a “Rating Color” column in an appropriate table. The data rows should 
follow the below mentioned convention.

Aggregate rating Rating color

Above 4.5 Dark Green

4 to 4.4 Green

3.5 to 3.9 Yellow

2.5 to 3.4 Orange

1.8 to 2.4 Red

0 to 1.7 White

2. Create following measures in appropriate tables. 

a. Restaurant Count

b. Average Cost

c. Average Rating

d. Cuisine Count

3. Create a new column called “Continent” in the “Country Code” table. Create the values 
using the below mentioned convention.

Note: The Country and Continent mapping is as follows. Please use this convention wherever 
needed.

a. Africa – South Africa 

b. Asia – Philippines

c. Asia – Singapore 

d. Asia – UAE

e. Asia – India

f. Asia – Indonesia 

g. Asia – Qatar

h. Asia – Sri Lanka 

i. Asia – Turkey

j. Europe – United Kingdom

k. North America – United States 

l. North America – Canada

m. Oceania – Australia

n. Oceania – New Zealand 

o. South America – Brazil

Step 5: Visualizations

1) Create the following visuals. 

a. Card visual

i. Average Cost

ii. Average Rating

iii. Restaurant Count 

b. Map visual

i. Geography hierarchy

ii. Restaurant Count

c. Infographic designer

i. Restaurant Name

ii. Top 5 Restaurants by Average Cost

iii. Average Rating

d. Slicer showing list of rating colours

e. Slicer showing list of counties

f. Slicer showing list of cities

g. Grid showing list of restaurants

h. Gauge showing selected restaurant’s average rating 

i. Gauge showing selected restaurant’s average cost

j. Card showing the selected restaurant’s address

k. Grid showing the selected restaurant’s list of cuisines

l. Publish the report on to a service account and create a public link.

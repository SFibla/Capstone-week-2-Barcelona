# Capstone-week-2-Barcelona

Capstone Project - The Battle of Neighborhoods (Week 2)  
BARCELONA RENTING HOUSE.

A full report consisting of all of the following components (15 marks):
 
 
Conclusion section where you conclude the report.

Introduction where you discuss the business problem and who would be interested in this project.
 

Currently I am living in the UK. I am planning on moving back to Barcelona in a short future.
In this scenario, I really need machine learning tools in order to assist me to make a wise and effective decision about which neighborhood is the best to rent a house.

I am going to cluster Barcelona neighborhoods in order to analyse how many and what kind of venues and the current average price of real estate.

The neighborhood will be segmented according to amenities and essential facilities surrounding such i.e. grocery stores, restaurants, pubs..
 
Background

CBRE’s Global Living report on the housing market in 35 of the world’s most important cities asserts that house prices increased the most in Barcelona last year, up 16.9%, with Madrid not far behind in fourth place with an increase of 10.2%. This comes as a surprise to locals in the business.
 
The problem with all international housing rankings like this one from CBRE that compares Spain to other countries is that the source data is not very reliable when it comes to house prices in Spain. CBRE cites the Spanish Notaries’ Association as the data source, but in my experience the Notaries’ figures are highly volatile, and are revised significantly months later. The statistics provided by the notaries are user-unfriendly, which makes it difficult to delve into them and work out what’s going on, but they never seem to match the reality described by property professionals.
No other source I can find thinks that Barcelona house prices rose by 16.9%. According to data from Barcelona City Hall, house prices in terms of €/m2 (built) were up 4.5% last year to 4,182€/m2, admittedly with new house prices up 17.7% to 4,619€/m2, but the much bigger resale market was only up 2.7% to 4,120€/m2.
Reports from agents at the coal face of the property market in Barcelona tell a similar story of low or stable Barcelona house prices last year. Alex Vaughan of Barcelona-based agents Lucas Fox reports an overall increase of 1.4% vs 2017, though the key Eixample district segment rose even less, but just 0.5% “That’s closed prices,” explains Alex. “Obviously the market was much slower last year, especially prime. This year has started very well, with the number of offers close to where they were in 2017 but I would say people are now willing to pay 10% less than they were before October 2017.”
 

 
Data where you describe the data that will be used to solve the problem and the source of the data
 


The main resource has been https://www.bcn.cat/estadistica/castella/dades/timm/ipreus/hab2mave/evo/t2mab.htm



I


Web barcelona ajuntament:
Filters applied and snapp


 
To explore and target recommended locations across different venues according to the presence of amenities and essential facilities, we will access data through FourSquare API interface and arrange them as a dataframe for visualization. By merging data on Barcelona properties and the relative price paid data from Ajuntament de Barcelona and data on amenities and essential facilities surrounding such properties from FourSquare API interface, we will be able to recommend profitable real estate investments.


3. Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, if any, and what machine learnings were used and why.
 
The objective is to build a table with the different neighborhoods, adding coordinates and the revenues. Statistical testing will share the city into 5 different clusters related with the price of renting.
Next table is merged neighborhoods and coordinates

Using folium to create a map of Barcelona with the different neighborhoods.

Using foursquare to find out the different venues.

 
c) The definitive table, neighborhood, coordinates, and venues with their coordinates
 
 

Using statistical tool to cluster the city of Barcelona in 5 differents clusters.

Using folium to create a map of Barcelona with the 5 different clusters 

Next snipping is an example of two clusters.

 
Results section where you discuss the results.
The statistical results reflect the difference between expensive and cheap neighborhoods. There is a relationship between the quality of venues and the price of renting.
The results split Barcelona mainly into two areas, the area near Tibidabo, Bonanova and the new neighborhoods near the sea.
L’eixample , both dreta and esquerra are in the same cluster, keeping the same offer in venues and similar renting prices.
Some areas like Parallel reflect a weak offer of venues and low prices.
Conclusion section where you conclude the report.
The algorithm is telling me:
There is exclusive and expensive renting with two options, mountain or see neighborhoods.
There is affordable renting mainly in dreta and esquerra eixample areas.
There is some cheaper renting with poor offer of venues in some areas like parallel.
 
 

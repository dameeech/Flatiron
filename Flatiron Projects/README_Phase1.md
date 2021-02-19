#                                    Boozapalooza Project Readme

Authors: Dimitry Belozersky, Theron Glynn

#                                                   Overview

Our goal in this project is to determine whether Boston or Denver make sense for the opening of Boozapalooza; our upscale bar and cocktail delivery service. Using only the Yelp API we managed to gather data on all the bars in both cities as well as their underlying attributes including average rating, location by zipcode, and price. 

We were able to determine that Denver is the better city for our business due to the concentraion of bars to a smaller geographic area and a reletivly afluent customer base for our premium cocktails.

#                                            Business Problem

Is Boston or Denver the best place to open an upscale bar and cocktail delivery service.
Which city has more total bars?
Which city has more bars that deliver?
Is the ability to deliver reflected in a bar's raiting? 
    - Are bars that deliver rated more highly then ones that don't?
Which city has more bars in a concentrated area?
    - A potential pain point for customers is having to travel to get to a bar.
Which city has more expensive bars to reflect our potential consumers?
    - We are a high-end delivery service so the more expensive bars in a city, the more potential customers we have!

#                                                       Data

We gathered data from Boston and Denver using the Yelp API. By pulling catagories for: Zip Code, Buisness Rating, Delivery Availability, Review Count, and Price for Boston and Denver we were able to perform a regressive analasis to determine the best city to open our Delivery Bar. We wanted to break down the total concentrain of bars by Zip Code and use the Business Ratings and Review Counts to justify our ultimate city decision. In addition we wanted to use Price to determine the amount of potential customers for our high-end bar by finding the areas with the most expensive bars.

#                                                    Methods

Using the Yelp API we were able to pull in every bar represented on Yelp in Boston and Denver. 
- First we looked at the amount in each city which showed us that they both had a similar amount with Denver slightly ahead of Boston.
- Next we looked at how many of the bars in each city offer delivery, which again did not offer a tremendous amount of insight.
- We then took a look at the ratings of bars in both cities and discovered that bars that deliver tend to have a very slight edge(about .5 points) over ones that don't. This confirmed that opening a Delivery Bar was a good idea but unfortunatly did not help us make a determination about which city we wanted to go with.
- Our next step was to see if one city had a bigger concentraion of bars in a single area and that finally gave us our first major insight. Boston bars were more evenly distributed whereas bars in Denver seemed to be concentrated in a few zip codes. That meant that it would make more sense to open a delivery bar in an area where people have to travel to get to the bars more often. Denver was starting to look like it had potential!
- Following our determination we decided to dive deeper into Denver to see if we could further justify our decision.
- We wanted to test our theory that the concentration of bars in those top 5 zip codes were catering to our potential afluent and picky customer base. To do that we made a graph representing the relationship between the average of all ratings and the total amount of reviews for the bars in those zip codes.
- We found that the zipcode with largest amount of bars had the lowest average ratings. This shows us that even in the most crowded space we have room to grow due to our quality products. 
- Finally we wanted to see a breakdown of categories within the bar space to get insight on potential ways in which we can differentiate ourselves from the competition.
- We found that while the biggest category was Bars, the rest of the most frequant categories were mostly related to restaurants and food. Building on this knowledge we are able to draw the conclusion that by using cocktails and cocktail delivery as our categories we would stand out from our competition as well as make it easy to find us if the consumer searches for those terms.

#                                                     Results

Through rigorus analysis we determined that Denver is the best future home for Boozapalooza. The concentraion of the majority of bars in a smaller area means that we have a large potential consumer base to tap into who aren't interested in traveling to get to a bar.

Given more time it would be great to bring in Census data in order to further narrow down our ideal neighborhood based on income level to have a fuller picture of our potential consumer base.

#                                          Repository Structure


```python
├── README.md                           <- The top-level README for reviewers of this project
├── Final_Project_Notebook.ipynb        <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
└── notes                               <- Other Jupyter Notebooks related to the project
```

# Capstone-Project
Capstone Project - The Battle of Neighborhoods (Week 1)

Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a problem that you can use the Foursquare location data to solve. If you cannot think of an idea or a problem, here are some ideas to get you started:

In Module 3, we explored New York City and the city of Toronto and segmented and clustered their neighborhoods. Both cities are very diverse and are the financial capitals of their respective countries. One interesting idea would be to compare the neighborhoods of the two cities and determine how similar or dissimilar they are. Is New York City more like Toronto or Paris or some other multicultural city? I will leave it to you to refine this idea.
In a city of your choice, if someone is looking to open a restaurant, where would you recommend that they open it? Similarly, if a contractor is trying to start their own business, where would you recommend that they setup their office?
These are just a couple of many ideas and problems that can be solved using location data in addition to other datasets. No matter what you decide to do, make sure to provide sufficient justification of why you think what you want to do or solve is important and why would a client or a group of people be interested in your project.

Introduction

This project will analyze the New York City data. First, we will find the most visited commercial shop according to the number of check-ins, then we will try to find the neighborhoods that are lacking the selected type of shop which could be potential business opportunity.

Target Audience

The target audience of this report is any one that is interested in opening a shop but have no idea what kind of and in which neighborhood.

Data Section

The data comes from Dingqi Yang from the following link https://sites.google.com/site/yangdingqi/home/foursquare-dataset. It contains 227,428 check-ins in New York city. The data contains a file in tsv format. Each file contains 8 columns, which are:

User ID (anonymized)

Venue ID (Foursquare)

Venue category ID (Foursquare)

Venue category name (Foursquare)

Latitude

Longitude

Time zone offset in minutes (The offset in minutes between when this check-in occurred and the same time in UTC)

UTC time

Application

We will find the most visited type of shop (commercial) according to the number of check-ins given in the data, then we will try to find neighborhoods that has none of this type of shop.

Examples are for 2000 venues, and the red dot is the center neighborhood which has the most number of Bars between selected coordinates. We did find two neighborhoods that are closest to it having none Bars within 4 kilometers.

   

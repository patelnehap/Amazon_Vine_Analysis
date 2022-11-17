# Amazon_Vine_Analysis

## Overview
Sellby project with Jennifer was quiet a learning curve and very successful as well. 
SellBy Stakeholders were so impressed with our work that we were tasked with another larger project : analyzing Amazon reviews written by members of the paid Amazon Vine program.
SellBy pays a small fee to Amazon and provides their products to Amazon Vine members so they can publish their reviews on Amazon site. SellBy would like to determine if there is a bias toward favorable reviews from Vine members.

## Results
Me and Jennifer had a brainstorming session to come up with ideas to approach the ask. We finally decided to set the threshold for the members who had voted for a total of 20 times or more. 

<img   src="https://github.com/patelnehap/Amazon_Vine_Analysis/blob/main/Images/GreaterThan20.JPG"  alt="Greater Than 20"  title="Greater than 20" style="display: inline-block; margin: 0 auto; max-width: 300px">

Also we needed to filter the dataset to a ratio of helpful votes to Ttoal votes by more than 50%.

<img   src="https://github.com/patelnehap/Amazon_Vine_Analysis/blob/main/Images/HelpfulVotes.JPG"  alt="Helpful Votes"  title="Helpful Votes" style="display: inline-block; margin: 0 auto; max-width: 300px">

Next we figured out the total number of reviewers and filtered the vine and non vine members out in the dataset.
Next we queried the dataset to get the 5 star vine and non vine member reviews and calculated the percentage of the 5 star reviews respectively. Below are the results:

<img   src="https://github.com/patelnehap/Amazon_Vine_Analysis/blob/main/Images/Total_Reviews.JPG"  alt="Total Reviews"  title="Total Reviews" style="display: inline-block; margin: 0 auto; max-width: 300px">

## Summary:

The above results indicate that the vine members were not biased in their reviews considering they were 10% less than non vine members (42% vs. 46.3%). So we can safely conclude that vine members are critical in their electronics review. 
We could run the analysis for the entire population vs only the helpful voters to solidify the outcome.
Aditionally we could run a statistical summary on the results to infer and support the above analysis.

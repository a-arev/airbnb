# Data Analysis for Airbnbs in Rio de Janeiro
## Description
This repo holds files and notebooks used to analyze a dataset from Airbnb. The dataset has app activity for Airbnb users in 
the city of Rio de Janeiro. The goal of this exercies is 
to answer the challenge found [here](https://colab.research.google.com/github/interviewquery/takehomes/blob/airbnb_1/airbnb_1/takehomefile.ipynb#scrollTo=eef90170), 
which are the following:

1.  What key metrics would you propose to monitor over time the success of the team's efforts in improving
    the guest host matching process and why? Clearly define your metric(s) and explain how each is computed.

3.  What areas should we invest in to increase the number of successful bookings in Rio de Janeiro? What
    segments are doing well and what could be improved? ​ ​Propose 2-3 specific recommendations (business
    initiatives and product changes) that could address these opportunities. Demonstrate rationale behind
    each recommendation AND prioritize your recommendations in order of their estimated impact.

5.  There is also interest from executives at Airbnb in the work you are doing, and a desire to understand
    the broader framing of the challenge of matching supply and demand, thinking beyond the data
    provided. What other research, experiments, or approaches could help the company get more clarity on the problem?

## Files
- **data** - a folder holding all datasets
  - **contacts.csv** - contains a row for every time that a user makes an inquiry for a stay at a listing in Rio de Janeiro.
  - **listings.csv** - contains data for every listing in the market
  - **users.csv** - contains data for every user (hosts and guest)
- **images** - a folder used for archiving useful tables and graphs from the analysis
  - **contact-channel.png** - table showings counts for each contact channel
  - **guest-country.png** - table showing top 5 countries where guests are from
  - **guest-user-stage.png** - table showing counts for guest user stage
  - **host-guest-first-message-length.png** - graph showing distribution of host-guest first message length
  - **host-guest-interaction.png** - graph showing distrubtion of host-guest number of interactions
  - **host-total-reviews.png** - graph showing distribution of total reviews of host
  - **listing-neighborhood.png** - table showing top 5 neighboorhoods for listings with bookings
  - **room-type.png** - table showing counts of each type of room for listings
  - **time-to-book.png** - graph showing distribution of booking time (time of booking minus time of inquiry)
  - **Airbnb Analysis Results.pdf** - PDF file for slide presentation on the analysis results 

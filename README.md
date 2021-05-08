# CMSC320 Final Project
Data choice:
  - Wanted to do music but spotify data had a limited timeframe, so we looked at Billboard instead.
  - Billboard dataset had data by week, which was too much, so we looked at an API instead.
  - API only had after 2006 so we instead decided to scrape the same data from wikipedia. 
  
Challenge Notes:
 - grabbed wrong table 2012 and 2013 and fixed by adding "wikitable" into find
 - "No." vs. no. symbol and fixed by renaming columns before adding 
 - One random additional entry, found that it was TIE??? which turned some of the rankings into string, the entry was listed as rank 100 in the magazine so we just set it to 100
 -  
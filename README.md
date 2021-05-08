# CMSC320 Final Project
Data choice:
  - Wanted to do music but spotify data had a limited timeframe, so we looked at Billboard instead.
  - Billboard dataset had data by week, which was too much, so we looked at an API instead.
  - API only had after 2006 so we instead decided to scrape the same data from wikipedia. 
  
Challenge Notes:
 - grabbed wrong table 2012 and 2013 and fixed by adding "wikitable" into find
 - "No." vs. no. symbol and fixed by renaming columns before adding 
 - One random additional entry, found that it was TIE??? which turned some of the rankings into string, the entry was listed as rank 100 in the magazine so we just set it to 100
 - Multiple versions of songs with slightly different values in parameters, which one do we pick?

Inital Run of Spotify Searches (1960): 4 missing 
 - 41 Anita Bryant Paper Roses -> Removed from Spotify [Link](https://open.spotify.com/track/7iehzxzmUvZZfuKFabo5no)
 - 58 The Old Lamp-Lighter -> The Old Lamplighter
 - 62 Image of a Girl The Safaris  & The Phantom's Band -> remove after &
 - 81 Tracy's Theme,Spencer Ross,1960 -> Not on Spotify

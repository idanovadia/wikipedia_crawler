# Wikipedia_crawler

## Environment
  - python 3.6 
  - jupiter nootbook file

## Description:

  this project use to crawling on wikipedia to find:
  
    1: Scrap the list of films Julia Roberts participated in from Wikipedia sorted by date. Present a
    readable table with the following fields per film: year, title, role and director(s).
    example: 
      Link: https://en.wikipedia.org/wiki/Julia_Roberts_filmography
    
    2: Scrap Wikipedia to create a list of all the actors who played with Julia Roberts on the same
    movie (any movie). Present a readable table with the following fields per co-actor\actress: name, year of
    birth, country of birth and number of awards that he\she got.
    
    3: Create a readable table which presents the number of joint movies for each co-actor\actress
    with Julia Roberts, and a histogram which presents the distribution of joint movies (number of co-actors
    per number of joint movies).


# Libs :
  ```
  from urllib.request import urlopen
  from urllib.error import HTTPError
  from bs4 import BeautifulSoup
  import re
  import pandas as pd
  import matplotlib.pyplot as plt

  ```


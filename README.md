# The impact of Covid-19 on suicide rate in the UK

![Suicide-prevention-week-awareness-web-824x549](https://user-images.githubusercontent.com/115706722/204639240-5241e6f1-d1eb-4871-bd40-3f665ee2e37f.jpg)

This is a team project that explored government datasets on suicide rates, comparing pre-pandemic and pandemic years.

## Contents

* [Dataset](#dataset-header)
* [Project Outline](#project-header)
* [Example Plots](#example-header)
* [Findings Reports and Presentation](#reports-header)
* [Dependencies and Setup Required](#dependencies-header)
* [How to View / Run the code](#how-header)
* [Jupyter Notebooks File Guide](#which-header)
* [Repository Structure](#structure-header)
* [Team](#team-header)

## <a id="dataset-header"></a>Dataset
The dataset for this project is from [the government health data website](https://fingertips.phe.org.uk/profile-group/mental-health/profile/suicide/data#page/9/gid/1938132828/pat/6/par/E12000001/ati/402/are/E08000024/iid/41001/age/285/sex/4/cat/-1/ctp/-1/yrr/3/cid/4/tbm/1/page-options/car-do-0) 

The original CSV file we accessed was broad in scope, with data extending to years of life lost due to suicide and admission episodes for alchohol-related conditions. For the purposes of this project we decided to narrow our scope to sucicide rate specifically and explored comparitave data from the 3 years prior to Covid-19 and the 3 years in which the pandemic took place. 

The are two main CSV files we used for our data and analysis:
* PreCovid.csv
* DuringCovid.csv


**Data Limitations**

Although our investigation was very interesting, and the plots we made from our findings were **"true"**, it is important to note that they do not **"tell the entire story".** It is also worth noting that certain covid specific conditions may influence the reliability of our data 

## <a id="project-header"></a>Project Outline


Hypothesis - A positive correlation between further 'x' laitidue suicide rates 



## <a id="reports-header"></a>Presentation and Findings


## <a id="dependencies-header"></a>Dependencies and Setup Required


* jupyter notebook `pip install notebook`
* pandas `pip install pandas`
* seaborn `pip install seaborn`
* matplotlib `pip install matplotlib`
* scipy `pip install scipy`

- import pandas as pd
- import matplotlib.pyplot as plt/mpl
- import numpy as np
- import scipy.stats as st
- %matplotlib inline
- import seaborn as sns

For the 'AreasAPI.ipynb' analysis, the additional dependencies will be required, inlcuidng an API key

* from api_key import geo_key
* import requests

## <a id="team-header"></a>Credits / Collaborators / Team
[Siobhan Brindley](https://github.com/SBrindley),
[Hardip Jandu](https://github.com/HJandu),
[James Hands](https://github.com/JamesHands18),
[Gussie Poole](https://github.com/gussiepoole)

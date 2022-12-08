# The impact of Covid-19 on suicide rate in the UK

![NHS-mental-health-plan-expansion-834845](https://user-images.githubusercontent.com/115706722/206465147-9fd6dd11-4b40-4e9e-bc3c-3ef5baa3daf3.jpg)


This is a team project that explored government datasets on suicide rates, comparing pre-pandemic and pandemic years.

## Contents

* [Dataset](#dataset-header)
* [Limitations](#limitations-header)
* [Project Outline](#project-header)
* [Findings Reports and Presentation](#reports-header)
* [Dependencies and Setup Required](#dependencies-header)
* [File Guide](#file-header)
* [Team](#team-header)

![Suicide-prevention-week-awareness-web-824x549](https://user-images.githubusercontent.com/115706722/204639240-5241e6f1-d1eb-4871-bd40-3f665ee2e37f.jpg)

## <a id="dataset-header"></a>Dataset
The dataset for this project is from [the government health data website](https://fingertips.phe.org.uk/profile-group/mental-health/profile/suicide/data#page/9/gid/1938132828/pat/6/par/E12000001/ati/402/are/E08000024/iid/41001/age/285/sex/4/cat/-1/ctp/-1/yrr/3/cid/4/tbm/1/page-options/car-do-0) 

The original CSV file we accessed was broad in scope, with data extending to years of life lost due to suicide and admission episodes for alchohol-related conditions. For the purposes of this project we decided to narrow our scope to sucicide rate specifically and explored comparitave data from the 3 years prior to Covid-19 and the 3 years in which the pandemic took place. 

The are two main CSV files we used for our data and analysis:
* PreCovid.csv
* DuringCovid.csv


## <a id="limitations-header">Data Limitations
Although our investigation was very interesting, and the plots we made from our findings were **"true"**, it is important to note that they do not **"tell the entire story".** It is also worth noting that although the data used in this project was sourced from the official government website, data gathered during covid cannot be used with absolute certainity of reliability.

## <a id="project-header"></a>Project Outline

We decided to investigate the affect of the pandemic on mental health. Our analytical focus was on the suicide rate before and during covid. 

Our target questions:
* Is there a link between sucide rate and an area's level of deprivation during Covid?
* Was there a regional difference in suicide rates before and during Covid?
* Was the gender split of suicide rates affected by Covid?
* How did suicide rates change during covid in the West Midlands?
* **Hypothesis** - A positive correlation between latitude and suicide rate

For each target question and hypothesis, we created a number of visualisations to display the data in a more understandable format and to help us analyse the information further

We used visulations such as grouped bar charts, pie charts, APIs and box plots to help analyse the data for our target questions. 


## <a id="reports-header"></a>Presentation and Findings

[The powerpoint presentation for this project]:(https://github.com/HJandu/Project_Group_2/blob/main/Project%201%20Presentation.pptx_)


  
Gender Analysis
-The percentage increase for suicide rate was greater for women (6.94%) than men (3.64%) *** covid.
-The gender split for suicide statistics is still overwhelmingly male, 
however during Covid was more in favour of the female gender.
-The split over the regions follows the same pattern as 
 
Regional Analysis
-The only regions to have a decline in suicide rate were the East of England and London. All other regions saw a rise in suicide rate during the pandemic.
  
-Our analysis showed that the proposed **hypothesis** was true, the p value we calculated indicated that there was a positive correlation between latitude and suicide rate during Covid.
 

Deprivation Analysis 
- The most deprived area had a drastic drop in suicide rate and the upper deciles had a sharp increase in suicide rates


More detailed analysis may be found in the PowerPoint Presentation


## <a id="dependencies-header"></a>Dependencies and Setup Required

* jupyter notebook `pip install notebook`
* pandas `pip install pandas`
* seaborn `pip install seaborn`
* matplotlib `pip install matplotlib`
* scipy `pip install scipy`

- import **pandas** as **pd**
- import **matplotlib.pyplot** as **plt/mpl**
- import **numpy** as **np**
- import **scipy.stats as st**
- **%matplotlib** inline
- import **seaborn** as **sns**

For the 'AreasAPI.ipynb' analysis, the additional dependencies will be required, inlcuidng an API key

* from api_key import geo_key
* import requests

## <a id="file-header"></a>**File Guide**
  
- **Initial file for cleaning and processing dat** - 'Cleaning' - Cleaning.ipynb
- **Clean CSV files ready for analysis** - PreCovid.csv, DuringCovid.csv
- **Filtered pre-covid CSV files for each category for analysis** (r=region, g=gender, a=area, w=deprivation) - PreCovid_a.csv, PreCovid_g.csv, PreCovid_r.csv, PreCovid_w.csv
- **Filtered during-covid CSV files for each category for analysis** (r=region, g=gender, a=area, w=deprivation) - DuringCovid_a.csv, DuringCovid_g.csv, DuringCovid_r.csv, DuringCovid_w.csv
- **Analysis by Gender** - 'Gender' - Comparison stacks.ipynb
- **Data for regions** - West Midlands - west_midlands_pre.csv, west_midlands_during.csv, indicators-CountiesUAsfromApr2021.data.csv
- **Analysis by region** - AreasAPI.ipynb, Data by region.ipynb, region_anova_hypo.ipynb
- **Analysis by region** - West Midlands - County -WestMidlands.ipynb, West midlands During-Covid map.ipynb
- **Analysis by deprivation** - 'Deprivation' - WealthBased.ipynb
- **PowerPoint Presentation** - Project 1 Presentation.pptx
- The 'Output' Folder encloses the png images of our visualisations

## <a id="team-header"></a> Team
[Siobhan Brindley](https://github.com/SBrindley),
[Hardip Jandu](https://github.com/HJandu),
[James Hands](https://github.com/JamesHands18),
[Gussie Poole](https://github.com/gussiepoole)

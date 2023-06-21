
<img src="https://www.york.ac.uk/media/research/images/impactcasestudiesgeneral/global-health-challenges800x400.jpg" alt="Global Health Image" title="Global Health  Image">

# Predicting Life Expectancy at Birth with International Metrics
*Seamus Walsh and Daniel Gieseke  |  June 23, 2023*

## Overview
Life expectancies vary over countries globally. With this project we are aiming to create a model that will predict a country's life expectancy at birth based on a variety of factors. Not only is this project focused on building a strong predictive model, this project further aims to look into which country features prove to be the most important when considering life expectancy at birth. This data was sourced from The World Bank and the United Nations via Kaggle.

## Project and Data Links
<a href="https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/blob/main/Final%20Edit%20-%20Movie%20Data%20Visualization%20Project.ipynb">Main Project File</a>

<a href="https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/blob/main/Exploring%20Movie%20Data%20Project%20-%20Slide%20Deck%20-%2005.12.2023.pdf">Project Slide Deck</a>

<a href="https://www.kaggle.com/datasets/truecue/worldsustainabilitydataset?select=WorldSustainabilityDataset.csv">Data Source: The World Bank and United Nations' Sustainability Data via Kaggle</a>

<a href="https://www.imdb.com/">Data Source: IMDB</a>

## Business Understanding
For this project we have assumed Microsoft, a large technology company with an immense amount of capital, has decided to open a movie studio; we have prepared our analyses and recommendations accordingly.  Throughout this project we honed in on data that we believe answers the following for the tech giant:
<ul>
  <li>Amount of money to invest to receive the highest return on investment.</li>
  <li>Genre to invest in to receive the highest audience favorability and return on investment.</li>
  <li>Optimal time of year for movie releases.</li>
</ul>

## Data Understanding
As we set out to explore relevant data, we imported several data sets from reputable media organizations and narrowed down our data sets by metrics we aimed to measure.  After importing data sets from Rotten Tomatoes, IMDB, Box Office Mojo, and The Numbers, we chose sets from IM.DB and The Numbers.  We imported both data sets into pandas data frames, cleaned data to ensure numerical values were readable as integers, dropped null and messy data, and for several visualizations we merged the data frames to compare 'genre', 'budget', and 'return on investment' data.

## Data Analysis
For our analyses we sought to answer and hone in on the three topics mentioned above:
<ul>
  <li>Amount of money to invest to receive the highest return on investment.</li>
  <li>Genre to invest in to receive the highest audience favorability and return on investment.</li>
  <li>Optimal time of year for movie releases.</li>
</ul>

Below are visualizations that we believe shed light on these points.  For additional narratives and context, please see our jupyter notebook file.


**Relationship between Production Budget, Worldwide Gross, and Return on Investment**
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/b6cde90d-de0f-4b3e-966e-e1247264852d)
*An increase in a production budget historically shows an increase in worldwide gross, however an increase in production budget has little to no effect on overall return on investment.*


**Genres by Audience Favorability and Return on Investment**
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/31b5b674-e51b-4b89-b2b7-3956506cd488)
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/d26653b5-f054-45f8-8563-6f4b0dfba525)
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/ff4e156e-e4ed-456f-ad32-3e8d3bcd7238)
*In comparing the graphs, we believe it may be worthwhile for a company to pursue a genre with high average rating as well as high average return on investment. We suggest a company entering the movie industry pursue movies in the 'animation' genre as these films yield high median audience ratings as well as high return on investments.*

**Relationship between Movie Release Month and Return on Investment**
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/a3343dd7-2cf9-4fdf-90a6-103afcf7b8e0)
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/21627e14-1fe5-4bdd-8dd4-ad6a30b77bda)
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/32468677/f031e473-05a3-4c8b-afd1-29fc029fd9a2)
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/32468677/9a75a993-fa5e-4e15-bafb-d462dbc9a890)
*Based on our analysis of this data, we believe July to be the best month to release an animated movie to see a higher ROI and a safer month to choose for a company entering the movie industry. Although June looks like a better month, overall, when removing outliers, we see that the ROI is not quite as strong compared with some other months. So we went a step further with our third chart to map out ROIs specifically for animated movies, and found July to have the strongest ROI. Then looking specifically at July ROI's across genre's this doubles down on our findings above that a company looking to enter the market and plan for a July release should focus on the 'animation' genre. Horror being the only genre with a higher ROI in July, but as we saw earlier, much poorer ratings.*

**Market Share by Genre Overtime**
![image](https://github.com/DGieseke/Exploratory-Data-Analysis-Using-Movie-Data/assets/130595612/30f9c117-ee96-4af2-8a77-5847732195ea)
*Animation proves to be an optimal choice for investment given its growing market share*

## Recommendations
<ul>
<li>Recommend lower production budget because of less ROI as budget increases
<ul class="square">
  <li>3 potential genres (Animation, Horror, Sci-Fi)</li>
  <li>Initial analysis showed that Horror was also very high in ROI, but when looking at median average rating, it is the lowest ( so people don’t like those movies as much) whereas Animation was one of the highest</li></ul>
<li>Release movie in June
 <ul class="square">
   <li>Recommending the Animation genre</li>
   <li>Specifically an animated movie in June based on the previous explained analysis</li></ul>
</ul>

## Next Steps
<li>Partnership with industry leaders?
<li>Types of animation?
<li>Where should the money go?
<li>Social factors?

## Repository Structure
  <b>daniel folder</b> This folder houses Daniel's working documents.

  <b>seamus folder</b> This folder houses Seamus's working documents.
  
  <b>Exploring Movie Data Project - Slide Deck</b> This file is a slide deck covering our analysis.
  
  <b>Final Edit - Movie Data Visualization File</b> This file contains our analyses, code, narrative, and visualizations.
  
  <b>README.md</b> This is the file you are reading now that gives an overview of our project.

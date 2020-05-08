## South Korea's COVID-19 Data Analysis

### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [Repository Structure / Files](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code assumes you use Anaconda (Python 3) with the following extra libraries installed: geoplot, geopandas, shapely (use the following installation command): `conda install -c conda-forge geoplot geopandas shapely`

## Motivation<a name="motivation"></a>

As part of the activities of Udacity's Data Science Nanodegree I'm enrolled, I have to choose a publicly available dataset and run a data analysis on it. I wanted to do something which would be relevant to the current world context. As we are going through the COVID-19 pandemic, I decided to build my project on this subject. For this analysis, I use [South Korea's publicly available COVID-19 dataset](https://www.kaggle.com/kimjihoo/coronavirusdataset), aiming at answering the following questions:

1. How did the disease spread within the provinces over time?
2. What characteristics are good predictors of the patient status?
3. What are the riskiest locations for COVID-19 infection in Seoul (where infected people have visited the most)?

## Repository Structure / Files <a name="files"></a>

- The `data` folder comprises the dataset's data as well as Seoul's shapefiles, found in [this publicly available repo](https://github.com/southkorea/seoul-maps). 

  * The draft notebooks are more exploratory and thus contain less documentation and the steps are not necessarily follow a structured line of thought.
  * The final notebooks are revised and documented versions of the drafts, and were responsible to generate the visualizations and results of the analyses.
  * There is a notebook named full-analysis within the fila notebooks folder. It contains a full version of the analysis with code, images, documentation, results and insights.
- The `code` folder contains the draft and final notebooks for each of the analysis questions stated above. 
- The `assets` folder contains the images generated for each of the analysis questions stated above, which are used in the final report post.

## Results<a name="results"></a>

By using Data Science concepts and techniques, I was able to analyze South Korea's publicly available COVID-19 data and get some interesting insights about the infection curves in the Provinces of the country, as well as investigate how variables like age, sex and infection type influence patient status, and finally get a sense for which neighborhoods in Seoul are the riskiest to infection by the virus; correlating the analyses results with news and events from the pandemic chronology in the country.

A more detailed description of the project, its analyses and insights can be found at the post available [here](https://medium.com/@tarcisocomp/stop-relying-on-your-gut-and-go-data-driven-insights-from-south-koreas-covid-19-data-929204190a1b).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to [South Korea's Github organization](https://github.com/southkorea) for the shapefile data. You can find the Licensing for the COVID-19 data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/kimjihoo/coronavirusdataset). Feel free to use the code provided that you give credits / cite this repo, as well as to contribute.

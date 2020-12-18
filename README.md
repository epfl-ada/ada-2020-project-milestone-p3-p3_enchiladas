# ada-2020-project-milestone-p3-p3_enchiladas
ada-2020-project-milestone-p3-p3_enchiladas created by GitHub Classroom


## Title: Analysis of the effect of ethnicity on food consumption in London

## Abstract: 
The objective is to extend the Tesco dataset with a dataset containing numerous interesting socio-economic statistics in the London area. The analysis focuses on LSOA regions, which is the finest resolution available in the Tesco dataset. The proportion of inhabitants from various ethnicities is given for each LSOA in the additional dataset. We will first analyze the effect of ethnic diversity on food purchase. It will be based on the comparison of diversity of food categories consumed across LSOA regions and their ethnic diversity. We will then try to validate the observations we made by assessing if they still hold when other socio-economic aspects (such as mean wage for example) are taken into account. Depending on the results found, we will also investigate in greater details what impact specific ethnic populations may have on the food purchase.

## Research questions:
Does ethnic diversity have an effect on food purchase at area level? And if yes, what is its nature?
To which extent is the ethnic diversity responsible for the food purchase diversity of some aliment categories?
Can we attribute particular purchase habits to specific ethnic groups?

## Proposed dataset:
We will use the dataset from our paper (Tesco Grocery 1.0, a large-scale dataset of grocery purchases in London) as the main source of information. We will further extend the data presented in the paper with the LSOA atlas (https://data.london.gov.uk/dataset/lsoa-atlas), an official summary of demographic data for the city of London for the year 2011, aggregated at LSOA level. Some of the information present in this dataset was already used by the authors of the Tesco paper to compute their representativeness metric. We are therefore confident that this dataset is well suited for enriching the Tesco dataset. 
The dataset from the paper is already very interesting. Indeed, besides the nutrients information used in the validation analysis of the paper, this dataset offers information on the purchases of different products at the area level. By adding the socio-economic dataset of the LSOA, we will be able to combine the data on food consumption with information about ethnicity as well as other socio-economic factors.
In addition, a dataset of the geographical information of the LSOA will be used (https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london) for visualization purposes. This will allow to display some of the results on the London map with relevant values assigned to each geographical region representing the LSOA. 

## Methods:
- Clean the data. 
- Filter the data to only keep the most representative areas for our analysis. We will use the representativeness metric introduced in the paper to ensure that we filter the areas as necessary.
- Analyse the distributions of the food categories consumed and their diversity at area level.
- Analyse the distributions of ethnicities proportions at area level.
- Compute a food categories diversity metric using the data from the Tesco dataset (different from the nutrients entropy).
- Compute an ethnic diversity metric for each LSOA and run statistical tests to see if it has an influence on food consumption diversity.
- Assess the effects of other socio-economic factors such as the mean wage or the employment rate.
- Visualize the results using clear and esthetic figures. 

## Proposed timeline:
### 1st week: 
- Clean and filter the data
- Merge the dataset
- Compute metric of diversity for both ethnicity proportions and food categories
- Analyze the distributions of ethnicity entropy, food product categories entropies as well as several other features that could act as confounders across LSOA
### 2nd week:
- Compute correlations between our ethnic features and food products categories features to see if we observe relations
- Run statistical tests to see if there is a significant correlation between ethnic diversity and food consumption diversity
- Add socio-economic metrics to the analysis and check if the effect of ethnic diversity is still significant on food consumption diversity
- Linear regression analysis
- Generalised proposity matching analsis
- Start writing the report 
- Start doing some neat visualizations of our results
### 3rd week:
- Conclude our analysis
- Perfect our data/results visualization
- Fine tune the report

## Organization within the team:
- Definition of slots of time where we work in parallel
- Weekly meetings to discuss the work that has been done
- Every group member will take part in all stages of the project

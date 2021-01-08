# CASA0005

This repo will contain the .Rmd file and .R file with the goal of GIScience final assessment.

# Inspiration

The cartographic and GIScience topic

EV charging (New energy & Sustainable)

    - [Dataset](https://www.gov.uk/guidance/find-and-use-data-on-public-electric-vehicle-chargepoints#accessing-data-on-ncr)

# Inspiration to Reality

## One problem:

How can I find the relationship between EV charging location and another factor?

1. CO<sub>2</sub> emission

2. Type of connector(existing col **connector1Type** in dataset)
   
   - 3-pin Type G
        ![3-pin Type G](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTR2CDebAo0QlfNYTSymDB_jLFqoLX1iOBQtA&usqp=CAU)
    - Type 2 Mennekes
        ![Type 2 Mennekes](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBi4EZb95ZPUeR6xeXyIXwqefQZ_lZpHiskQ&usqp=CAU)
    - JEVS G105 (CHAdeMO) DC
        ![JEVS G105 (CHAdeMO) DC](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT1NWvSaEqT5k0lkSm4dCyXF3-QI5sy0BEunA&usqp=CAU)
    - Type 1 SAEJ1772 (IEC 62196)
        ![Type 1 SAEJ1772 (IEC 62196)](https://image.made-in-china.com/202f0j00tzBUkvRGqycT/SAE-J1772-Type-1-Electric-Plug-for-Cars-Charging-40A.jpg)
    - Type 2 Combo (IEC62196) DC
        ![Type 2 Combo (IEC62196) DC](https://sc01.alicdn.com/kf/HTB1tOizXHY1gK0jSZTEq6xDQVXa0.jpg)
    - Type 2 Tesla (IEC62196) DC
        ![Type 2 Tesla (IEC62196) DC](https://qph.fs.quoracdn.net/main-qimg-5c6e9331eace1a7546b9c41867387416)
    - Type 3 Scame
        ![Type 3 Scame](https://eco-motion.fr/5645-thickbox/sobem-scame-20033234-fiche-mobile-type-3c-avec-capuchon-bornes-a-vis-noir.jpg)

## How to write literature review?

- Standard: you can see in the [Zhenzi's blog](https://zen.zzzhou.me/Contents/X_M.html#quantitative-methods)

- Size: 

- Content:
    Policy
    Analysis
    Global Insights 

## Which method I need to choose to analysis?

- Moran's I analysis 墨兰指数？

- Hotspot analysis

- descrptive statistics

- interpolation

## How can I make the good map

- check legend, like below
  
  ![](https://andrewmaclachlan.github.io/CASA0005repo/CASA0005_files/figure-html/unnamed-chunk-274-1.png)

## 

# Data Source

- ![Data Source](DataSource.png)（mentioned in wk1 CASA0005 lecture）

- [PlanB: New York City Airbnb Open Data](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data/metadata)

- R dplyr cheatsheet:
  
    ![dplyr diagram](https://andrewmaclachlan.github.io/CASA0005repo/prac2_images/dplyr.svg)
1. Emotional cartographic: depression disturbtion temporal and spatial rules 
   
   - refer to the second assignment
   - Dataset:...

2. Analysis of female empolyment before and after covid-19
   
   - Dataset: Linkedin

3. Beer geographic

4. Uder things (It is from Zhengzi)
   
   - [Uber Analytics](https://github.com/uber/h3-py-notebooks/blob/master/notebooks/urban_analytics.ipynb)
   - [OSD Road Network Analysis](https://github.com/gboeing/osmnx-examples/blob/master/notebooks/09-example-figure-ground.ipynb)

5. The analysis of coffee shop
   
   - inspired via my undergrad projekt e-commerce work
   - distrubtion of cafe
   - in other perspectives, we can also analyse the Yelp/TripAdvisor restaurant/cafe

6. Disability equipment location in London, UK

7. [Coursera AI Global Skills Index 2019 data](https://www.kaggle.com/parulpandey/coursera-ai-global-skills-index-2019-data)
   
   - [Amazon](https://www.kaggle.com/atahmasb/amazon-job-skills)
   - [Google](https://www.kaggle.com/niyamatalmass/google-job-skills)

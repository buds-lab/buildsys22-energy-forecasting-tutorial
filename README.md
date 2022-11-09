# The first ACM BuildSys 2022 tutorial on electricity demand forecasting

### What is this tutorial about?
This tutorial is aimed at energy analysts, engineers, and researchers who want to learn more about machine learning algorithms that can be used to predict energy demand on several aggregation levels, ranging from the building level to districts and entire countries. At each of these aggregation levels, different challenges are faced by the load forecaster. We will demonstrate how aggregation levels as well as different forecasting algorithms and feature pipelines affect forecasting performance, and how these should be utilized in practice for best results. The tutorial will also include a collaborative coding session to offer participants a chance to practice demonstrated skills on datasets at various aggregation scales. The tutorial will also include a brief overview of where to find open-source energy demand datasets. The tutorial will conclude with a brief discussion on downstream tasks where such forecasts can be used in the energy sector.

### Link of used dataset:
[Smart meters in London](https://www.kaggle.com/datasets/jeanmidev/smart-meters-in-london)

It contatins energy consumption readings for a sample of 5,567 London Households that took part in the UK Power Networks led Low Carbon London project between November 2011 and February 2014.

### Notebooks
#### 0. [Data preprocessing](notebooks/)

This notebook will help you prepare a dataset for modeling by exporting aggregated datasets for different levels:
- City level
- Block level
- House level

#### 1. [EDA and modeling](notebooks/)

This notebook provides an overview of exploratory data analysis of the dataset and how to develop forecast models based on this analysis. Several different forecasting models will be developed and compared as follows:
- Persistence model (copy values from last week as predictions)
- Linear model
- LightGBM model (one of the most popular regression model on Kaggle)

#### 2. [Comparison between aggregation number of buildings](notebooks/)

This notebook is to compare forecasting performance between different aggregation number of buildings.
- 1000 buildings
- 100 buildings
- 10 buildings
- single building

#### 3. [[Exercise with blanks] Comparison between aggregation levels](notebooks/)

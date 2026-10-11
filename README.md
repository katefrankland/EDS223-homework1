# EDS 223 Homework 1: Air Quality and Income in San Bernardino County

## Repository Purpose

This repository contains Homework 1 for EDS 223 - Geospatial Analysis and Remote Sensing. This homework assignment explores an environmental justice issue through two related maps. I decided to compare annual-average PM2.5 concentrations with the percentage of low-income residents across census block groups in San Bernardino County, California, and try and see if there was a correlation between them. 

## R packages used 
- `tidyverse`
- `sf`
- `here`
- `tmap` 

## Maps Created

### Map 1: Annual-Average PM2.5 Concentrations

This map displays annual-average PM2.5 concentrations across census block groups.

![Map of PM2.5 concentrations in San Bernardino County](images/pm25_map.png)

### Map 2: Percentage of Low-Income Residents

This map displays the percentage of low-income residents across census block groups.

![Map of the percentage of low-income residents in San Bernardino County](images/income_map.png)

## Repository Contents

- `ej_screen.qmd`: Quarto document containing the code, maps, and explanatory paragraph.
- `images/pm25_map.png`: Exported PM2.5 map.
- `images/income_map.png`: Exported low-income population map.
- `README.md`: Project overview 

## Data Availability

This project uses the Environmental Protection Agency's 2023 EJScreen dataset supplied for the assignment. This dataset is no longer available for download on the EPA website. 

## Author and Instructor

- Author: Kate Frankland
- Instructor: Annie Adams 
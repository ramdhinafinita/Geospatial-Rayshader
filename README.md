# Geospatial-Rayshader
Geospatial Data Visualization with Rayshader in R

## Overview

The following coursebook is produced for [Algoritma](https://algorit.ma/)'s DSS [*Geospatial Data Visualization with Rayshader in R*](https://algorit.ma/geospatial-rayshader/) workshop.

The primary objective of this course is to provide a participant a comprehensive introduction about tools and software for visualizing a geospatial data using the popular open-source tools: R

## Modules

- [Part 1. Brief Introduction to R](intro-to-R.Rmd):
    * **Dasar Bahasa Pemrograman R**      
        + Pengenalan bahasa pemrograman R   
        + Bekerja dengan RStudio  
        + Fungsi standar pada R
          
    * **Data Wrangling dan visualisasi dengan R**  
        + Data manipulasi dan persiapan data menggunakan R `dplyr`
        + Working with tabular data in R: Tips and Techniques 
        + Data Wrangling and Aggregation
        + Introduction to visualization with `ggplot2`

- [Part 2A. Geospatial in R](Inclass_Spatial2D.Rmd)
    *  **Introduction to Geospatial Data** 
        - Data Spasial:  
          - Data Vektor -> Introduction to Manipulation Data
          - Data Raster -> Introduction to Manipulation Data
          - Representasi sederhana
          
        - Reading and Writing spatial data
          - File Vektor
          - File Raster
        
        - Sistem Koordinat Referensi
          - Coordinate Reference Systems (CRS)
              - Angular coordinates
              - Projections
              - Notation
          - Assigning a CRS
          - Transforming vector data
          - Transforming raster data
    * **Membuat Peta Interaktif**
        - Pengenalan tentang Peta Interaktif
        - Menggunakan Leaflet - API JavaScript untuk membuat peta interaktif
        - Membuat Peta Tematik Interaktif
    
- [Part 2B. Membuat Peta 3D dengan Rayshader](Inclass_Spatial3D.Rmd)
  - Pengenalan tentang Pustaka Rayshader
  - Memahami Konsep Pemetaan Topografis
  - Membangun Peta 3D dari Data Topografis Spatial.


## R packages

Following packages are used within the material:

```r
# packages <- c("readr", "readxl", "stringr","dplyr", "rgdal","sf", "maps", "leaflet", "raster", "osmdata", "ggplot2", "terra", "rayshader", "raster", "dplyr", "ggplot2", "car", "leaflet", "RColorBrewer", "magick", "animation", "osmdata", "viridis", "terra")

install.packages(packages)
```

## References

- [Kristin Stock, Hans Guesgen, in Automating Open Source Intelligence, 2016](https://www.elsevier.com/books/T/A/9780128029169)
- [Edzer Pebesma, Daniel Nüst, and Roger Bivand, “The R Software Environment in Reproducible Geoscientific Research,” Eos 93 (2012): 163–164.](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2012EO160003)  
- [Edzer Pebesma, Roger Bivand, Spatial Data Science](https://keen-swartz-3146c4.netlify.app/)
- [Robin Lovelace, Jakub Nowosad, Jannes Muenchow, "Geocomputation with R"](https://geocompr.robinlovelace.net/spatial-class.html)
- [Leaflet for R](https://rstudio.github.io/leaflet/)
- [Wilkinson, Leland, and Graham Wills. 2005. The Grammar of Graphics. Springer Science+ Business Media.](https://www.springer.com/de/book/9780387245447)
- [Paula Moraga, Geospatial Health Data: Modeling and Visualization with R-INLA and Shiny, 2019](https://www.paulamoraga.com/book-geospatial/index.html)

    

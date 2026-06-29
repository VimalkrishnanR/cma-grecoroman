 
# For the Benefit of all the People Forever: Greek and Roman Art Collection at the Cleveland Museum of Art

### Lede Program - Project 1 

## Overview

Project webpage: [For the Benefit of all the People Forever: Greek and Roman Art Collection at the Cleveland Museum of Art](https://vimalkrishnanr.github.io/cma-grecoroman/)

In this project, I am offering a brief data-visual interpretation of the Greek and Roman art collections held by the Cleveland Musuem of Art (CMA). The CMA, opened in 1916, is celebrating its 110th anniversary this year. In my story I discuss how CMA's early identity was forged by a classical Greco-Roman aesthetic. In this context, my story visualises data related to the current Greek and Roman art collection held by the CMA. 

## Data Collection Process 
The primary source of my data is the open access api offered by the CMA. Data is available in CSV, Json, and API formats here:
https://openaccess-api.clevelandart.org/
https://github.com/ClevelandMuseumArt/openaccess

As I focused on the Greek and Roman Art department, I used the official name of the department (Appendix B - API documentation) as a filter in the 'department' parameter to narrow down the scope of the json data. Using Requests, I imported the json data (refer to the notebook Cleveland.ipynb in the 'analysis' directory) into a pandas dataframe. 

## Data Analysis Process

Some of the primary questions that I wanted to answer are as follows: 
1. What is the overall current composition of the Greek and Roman Art Department, at CMA? 
2. What are the different types fo artworks held by the department? 
3. What are they made out of? 
4. Exhibition and Citation history: 
 - 4.1: Compared to other departments, how widely have artworks in the Greek and Roman Art Department been exhibited? 
 - 4.2: Which is the most cited and most exhibited artwork within the department and within the museum's entire collection?
 - 4.3: Which are the artworks, currently held by Greek and Roman art Department, that were part of the inaugural exhibition?
Due to technical constraints and to allow for deeper practice with pandas, I streamlined the scope of the project. I focused on questions 1, 2, 3, and 4.3. 

The data analysis involved identifying the categories/columns that were relevant for my questions and making dataframe subsets. I used the pandas package for casting the json data into a dataframe and for further analysis like value counts and cross tabulations. 

## Skills learnt 
This project has been an enriching experience. I could refine my technical skills in the application of python, pandas, HTML, CSS, and data visualisation tools like Flourish. I also learnt how data analysis and visualisations work best when they complement an overarching narrative.

## Future Work
I hope to return to this project to do deeper analysis in pandas and to design a website that is more visual and interactive in nature. I hope to explore libaries like D3, three.js and and other graphic and web design 

## References: 

1. [I read poetry for work. You get to read it for pleasure.](https://www.washingtonpost.com/opinions/interactive/2026/poetry-month-reading-pleasure/)
2. [Walt Disney Studio's Drawing on the Past](https://www.reuters.com/graphics/DISNEY-100/HISTORY/znvnzmzgjvl/)
3. [Shall we call it the Metropolitan Meow-seum of Art? Cats rule the canvas in art galleries at The Met museum](https://surbhi-bh.github.io/cats-at-the-met-museum/)
4. [Page Templates](https://jsoma.github.io/page-templates/)
5. [1970.16 Neck Amphora](https://sketchfab.com/3d-models/197016-neck-amphora-0bb2525bdd734bf69d5a7b2b051928ad)
6. [Catalog of the inaugural exhibition, June 6-September 20, 1916](https://library.si.edu/digital-library/book/catalogueinaugu00clev)
7. [Catalogue of the inaugural exhibition : June 6-September 20, 1916](https://library.si.edu/digital-library/book/catalogofinaugur00clev)
## Acknwoledgements: 
I thank my instructors Jonathan Soma, Aaron Reiss, and Sandhya Kambhampati. I also thank Carson TerBush for her mentorship. 



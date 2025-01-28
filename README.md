# ASUC Contingency Fund FY24 Cleaning and Analysis Project

## Purpose
I initiall envisioned this project out of a desire to understand how previous finance committees went about allocating money out of the contingency fund. As I did cleaning and analysis I eventually developed a large pool of data cleaning functions and developed some performance indicators. This repository then and the EDA + ETL notebook in particular serves as a record of my work developing cleaning functions, doing data analysis and developing performance indicators (just one metric for now).

The cleaning functions I've developed can be used to make crucial datasets more accessible. You can find more well-design versions along with full pipeline functions in the 'ASUC-Explore' repository also on my github. The data analysis I do here while rough already reveals some insights about the way the finance commitee does things and prompts further research. Finally the Expected Cumilative Difference (ECD) metric can be used as an indicator that's more sensitive to over/under allocation as time progresses.

## Sections
There's a raw dataset section, cleaning section, analysis section and ECD section. The raw dataset section simply introduces the datasets I'm working with, the cleaning section focuses on how I cleaned the datasets as well as the development behind the cleaning functions. The analysis section focuses on analyzing trends in club registration and Contingency funding allocation. This includes analysis of funding trends across time, by club type and more. Finally the ECD section introduces ECD, the idea behind it and how it can be used. 

## Data
The exact dataset CSV files are not in this repo for privacy but I introduce the structure of the datasets in the notebook. The data is primarily drawn from OASIS club registration spreadsheets, ASUC internal reports and ASUC meeting agendas. Everything except the meeting agendas are cvs, the meeting agenda documents are txt files.

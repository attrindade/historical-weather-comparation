# Comparing Porto Alegre's weather data from the last two decades

A comparison of the last two decades (2001 - 2021) of weather forecasting data from Porto Alegre.

## Table of Contents
* [Installation](#Installation)
* [Project Motivation](#motivation)
* [How to get the data](#get-data)
* [Project Overview](#p-over)
  * [Data Extraction](#p-extraction)
  * [Data Preparation](#p-preparation)
    * [Creating a Summarized Table](#p-summarized)

## Installation <a name="Installation"></a>

The code requires Python versions of 3.* and general libraries available through the Anaconda package. 

## Project Motivation <a name="motivation"></a>

As a citizen of Porto Alegre for more than 25 years I started to have the feeling that our weather is changing a little on these last years. Out of curiosity I wanted to visualize what differences are perceptible.

This is a simple project intended only to consolidate my knowledge of pandas, matplotlib and seaborn as I'm currently deepening my comprehension of them. I'm not offering a deep and solid analysis of Porto Alegre's weather changes along the years. My only plan is to learn and to see if my sensory perception of the city's temperatures seems to be in line with the data or not.

## How to get the data <a name="get-data"></a>

I got this .csv file with historical data from Porto Alegre from the INMET (Instituto Nacional de Meteorologia) website. It's very simple to get the data in the way want (specific variables, date range, etc). You can go to https://bdmep.inmet.gov.br/ (the INMET database website) and ask for it, it gives you many options to customise your data. The data (.csv) I've used in this project you can find on this repo as "DATA_POA_2001-01-01_2022-03-11.csv".

## Project Overview <a name="p-over"></a>

Filler.

### Data Extraction <a name="p-extraction"></a>


<table border="1" class="dataframe"> <thead> <tr style="undefined:undefined"> <th></th> <th>Data Medicao</th> <th>PRECIPITACAO TOTAL, DIARIO (mm)</th> <th>TEMPERATURA MAXIMA, DIARIA (C)</th> <th>TEMPERATURA MEDIA, DIARIA (C)</th> <th>TEMPERATURA MINIMA, DIARIA (C)</th> <th>UMIDADE RELATIVA DO AR, MEDIA DIARIA (%)</th> <th>UMIDADE RELATIVA DO AR, MINIMA DIARIA (%)</th> <th>Unnamed: 7</th> </tr> </thead> <tbody> <tr> <th>0</th> <td>2001-01-01</td> <td>0</td> <td>30,1</td> <td>23,616667</td> <td>18,4</td> <td>68,458333</td> <td>48.0</td> <td>NaN</td> </tr> <tr> <th>1</th> <td>2001-01-02</td> <td>0</td> <td>32,1</td> <td>25,475</td> <td>20</td> <td>69,958333</td> <td>45.0</td> <td>NaN</td> </tr> <tr> <th>2</th> <td>2001-01-03</td> <td>0</td> <td>33,4</td> <td>26,345833</td> <td>21</td> <td>69,083333</td> <td>43.0</td> <td>NaN</td> </tr> </tbody></table>

Filler.

### Data Preparation <a name="p-preparation"></a>

Filler.

#### Creating a Summarized Table <a name="p-summarized"></a>

Filler.

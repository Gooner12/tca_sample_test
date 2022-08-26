# Job Analysis for TCA

## Overview

This project involves analysing the Australian labour data for the tech industry spanning from 1984 to 2021. The data used in this analysis is obtained from www.abs.gov.au. All the analysis operations and insights are presented in the Jupyter notebook. 

## Methodology

In this project, to analyse the trends and to develop insights, two methods are used primarily. They are:

1) Data Visualisation: In this method, various types of graphs are generated to study the patterns, and the study is based on the combination of insights from multiple charts.

2) Forecasting: In this method, we used the SARIMAX algorithm to predict future points. The performance of the forecasting algorithm is assessed, and the forecasts till 2025 are obtained.

## Assumptions

1) The relevant tech industries are selected based on the information available on the labour market information portal, and there is a chance that there is an inclusion of non-tech roles in those selected industries. 

2) While selecting the relevant tech occupations, short research and personal judgement were used. So, there might be a presence of judgemental bias in the occupation selection process. Due to this, we might include some non-tech people and exclude some tech people. 

3) The old definition of states and territories is assumed to be the same as the present-day states and territories. In our data preprocessing steps, we merged different divided geographical regions into a single state, such as NSW, Greater Sydney and Sydney, into NSW. This transformation has been applied to relevant states.

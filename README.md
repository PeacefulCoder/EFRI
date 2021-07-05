# Energy as a Fundamental Right - EFRI - Simulation Model

## Summary
- The goal of this model is to minimize energy poverty by finding the optimum amount of free electricity.
- The simulation model tries millions of combinations of free electricity per household and per resident.
- Results are visualized and compared with the initial energy poverty status.
- An R Notebook, HTML output and its PDF is shared along with a sample data for step by step application.

## Background and Further Explanation
Electricity has become a basic need for almost every individual considering its effect on health, security, and even education. Many low-income households suffer from energy insecurities, reduce basic needs to afford energy bills, and live in in unhealthy conditions. Although social tariffs and energy assistance programs alleviate these issues to a certain extent, a considerable number of households still suffer from energy poverty. Additionally, due to the interdependent nature of the electricity market, the excess electricity usage of other households increases the electricity unit prices and exacerbate the energy poverty issues. As a solution, a certain amount of residential electricity can be provided for free to the households. The examples of Flanders, Belgium, and Delhi, India are the first implementations of such a system. On the other hand, it is very difficult to determine the optimum amount of free electricity considering many socio-economic parameters such as energy consumption habits, electricity prices, number of residents and income levels. This study aims to answer the question: “What would be the optimum residential free electricity amount which would reduce the energy poverty issues most?”.

The “Energy as a Fundamental Right (EFRI)” simulation model is developed to answer this question. Six indicators are considered for measuring energy poverty: average ratio in income of all households, average ratio in income of low-income households, median ratio in income of all households, median ratio in income of low-income households, number of energy poor households, number of energy poor residents. The model is designed to be self-sufficient such that the residential unit price of electricity is increased to a certain level to compensate the free electricity amounts. The optimum free electricity amount per person and per household is calculated by creating an equilibrium between rising unit price of electricity and the amount of free electricity.

## Sample Input Data
The EFRI simulation model is tested on the 2015 Residential Energy Consumption (RECS) data of the USA. Optimum free electricity amounts are calculated for the Middle Atlantic region for each simulation indicator.

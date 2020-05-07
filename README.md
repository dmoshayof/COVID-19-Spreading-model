
## COVID-19 Spreading Model
Vizualization model for COVID-19 spreading with diffrent number of creatures and isolation options.
From N creatures 1 creature is sick at 1st life cycle and keep spreading throw life cycles.
Each I cell has 8 neighbours who might be sick and infect the I cell in probability P.
No recovery options.

## Inputs
- N: Number of creatures 
- K: 0-8 isolation parameter (exmp: k=3 only 5 neighbours are considered in infection)
- Life Cycle of isolation: at what life cycle does isolation begin

## Description

white cell- Healthy
Blue cell- empty
Red Cell-Sick

## Requirements

- tkintr
- matplotlib
- numpy




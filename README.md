# How International Talent Shaped the Modern NBA

A research-style paper, written in R and Quarto, comparing
international and domestic NBA players across three eras.

Formatted with the open-source SportRxiv Quarto template. This is a
class project and has not been submitted to or published by SportRxiv.

## Question
As the NBA moved toward floor spacing and three-point shooting, did
international players adapt to that shift or help lead it?

## Data
Player-season records from 1996 to 2022, originally from the NBA
Stats API and downloaded from Kaggle: [paste the dataset link]

## Methods
- R with tidyverse, ggplot2, knitr and kableExtra, written in Quarto
- Split seasons into three eras: 1996–2004, 2005–2014 and 2015–2022
- Compared usage rate and true shooting percentage for players born
  in and outside the USA
- Fitted linear trend lines of true shooting percentage on usage for
  each group in each era, using seasons with more than 10 games played

## Findings
- At comparable usage rates, the international trend line sits above
  the domestic one in all three eras
- The number of international players rose steadily over the period
- League-wide, average height stayed near 200 cm while average weight
  fell from 101.1 kg to 98.6 kg

## Limitations
- Comparing trend lines is descriptive. It shows an efficiency gap,
  not that international players caused the league's shift
- The data has no position field. International players may skew
  toward big men, who tend to shoot more efficiently, and that could
  explain part of the gap

## Files
- `Joshua_Seo_Project_3.qmd`: source code and text
- `Joshua_Seo_Project_3.pdf`: rendered paper
- `bibliography.bib`: references

Completed as a class project at UCLA, Spring 2026.

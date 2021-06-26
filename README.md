# Police and lethality in Rio de Janeiro

# Methodology

Data from Rio de Janeiro's government is the main source [ISP Dados](http://www.ispdados.rj.gov.br/) for this analysis. The Python Notebook read longitudinal data directly and then I used simple averages to understand how deaths caused by polices and polices deaths have been evolving over the years.

The analysis uses mainly three columns:

- `ano`: year
- `hom_por_interv_policial`: deaths caused by police.
- `pol_militares_mortos_serv` (transformed to `cop_killed`): police deaths *during worktime*.


## Shortcomings

We just have data for the last two columns above starting from 2012.

## Summary

The analysis groups all register by year and then, in order to compare the current year with the previous one, estimates an average of deaths per day, both for polices and other citizens. While the deaths caused by police are almost reaching its historical maximum value, police deaths during worktime are decreasing in the last years. Since 2015, there are 173 registers of police deaths during worktime. The value for deaths caused by police is 7290. In other words, for each police death we have 42 homicides of other citizens.

---

Read more in [story.md](story.md)
# Crime and Wealth in the Netherlands
**Group 7** — Sterre de Groot, Benthe Tromp, Lars van der Duin, Sophie Thoolen, Roos Bakker  
**Tutorial lecturer:** Chantal Schouwenaar

## Research Question
"Dutch municipalities with higher income inequality have a higher number of recorded violent crimes per 1,000 inhabitants."

## Reproducibility

### Step 1 — Download the data
Download the files via the links below and save them in the `data/` folder of the project:

| File | Source | Link |
|---|---|---|
| misdrijven_2022_2023.csv | Data Politie | https://data.politie.nl/#/Politie/nl/dataset/47013NED/table?ts=1780489389758 |
| Misdrijven_2024.csv | Data Politie | https://data.politie.nl/#/Politie/nl/dataset/47013NED/table?ts=1780489389758 |
| vermogen_2022.csv | CBS StatLine | https://opendata.cbs.nl/#/CBS/nl/dataset/86160NED/table?ts=1780405280895 |
| vermogen_2023.csv | CBS StatLine | https://opendata.cbs.nl/#/CBS/nl/dataset/86160NED/table?ts=1780405280895 |
| Vermogen_huishoudens_2024.csv | CBS StatLine | https://opendata.cbs.nl/#/CBS/nl/dataset/86160NED/table?ts=1780405280895 |

### Step 2 — Restore the packages
Open the project in RStudio and run in the Console:
```r
renv::restore()
```

### Step 3 — Knit the report
Open `Template_Assignment.Rmd` and click **Knit**.
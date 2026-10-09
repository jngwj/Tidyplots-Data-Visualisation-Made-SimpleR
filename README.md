# `Tidyplots`: Data Visualisation Made Simple(R)

**A hands-on introduction to `tidyplots`** R confeRence 2026 Malaysia · Hands-on Workshop (2.5 hours) · Track 4: Pedagogy, Open Science & Scalable Onboarding

Facilitator: Associate Professor Dr. Jason Ng, Department of Business Analytics, Sunway Business School

------------------------------------------------------------------------

## About this workshop

`tidyplots` (Engler, 2025) lets you build publication-ready figures from one consistent pipeline: start a plot, then **add**, **remove** and **adjust** components. In this workshop you will build figures layer by layer from two Malaysian case studies, compare each with its `ggplot2` equivalent, and learn when to hand over to `ggplot2`.

By the end you will be able to:

1.  Explain the tidyplots workflow and its `add_<statistic>_<graphic>()` naming scheme.
2.  Build bar, line, area, heatmap, histogram, box/violin and scatter figures.
3.  Annotate group comparisons and state which test and adjustment is shown.
4.  Create small multiples with `split_plot()`.
5.  Extend a tidyplot with `ggplot2` layers via `add()`.

## Who this is for

Researchers, analysts, graduate students and business-facing team members who can run R code and recognise the pipe (`%>%` or `|>`). No `ggplot2` experience is required.

## Schedule

| Time      | Module                                      |
|-----------|---------------------------------------------|
| 0:00–0:10 | 0\. Setup and motivation                    |
| 0:10–0:35 | 1\. The tidyplots grammar (`study` dataset) |
| 0:35–1:10 | 2\. Case study: COVID-19 in Malaysia        |
| 1:10–1:20 | Break                                       |
| 1:20–1:55 | 3\. Case study: GE14, Peninsular Malaysia   |
| 1:55–2:15 | 4\. The ggplot2 escape hatch                |
| 2:15–2:30 | 5\. Your own data and wrap-up               |

------------------------------------------------------------------------

## Quick start (do this **before** the session)

### 1. Install the software

| Software  | Version tested      | Notes                         |
|-----------|---------------------|-------------------------------|
| R         | `4.6.0` or `4.6.1`  | <https://cran.r-project.org/> |
| An editor | Positron or RStudio | Any one is fine               |

Operating systems tested: macOS or Windows

### 2. Get the materials

``` bash
git clone https://github.com/jngwj/Tidyplots-Data-Visualisation-Made-SimpleR.git
cd Tidyplots-Data-Visualisation-Made-SimpleR
```

No Git? Click **Code → Download ZIP** on the repository page and unzip it.

------------------------------------------------------------------------

## R package dependencies

Packages used:

| Package | Used for | Version |
|------------------------|------------------------|------------------------|
| `tidyplots` | the workshop's main package | 0.40 |
| `tidyverse` (`ggplot2`, `dplyr`, `readr`, `lubridate`, …) | data preparation and ggplot2 comparisons | 2.0.0 |
| `ggstats` | proportion labels (`stat = "prop"`, `geom_prop_text()`) | 0.14.0 |
| `scales` | label formatting | 1.4.0 |

------------------------------------------------------------------------

## Datasets

All instructional datasets are included in this repository so the workshop works offline. **Hosting location** is the permanent source of each file.

| Dataset | Description | Original source |
|-------------|-------------|-------------|
| `covid_cases_state_monthly.csv` | Daily state-level COVID-19 cases from Malaysia's Ministry of Health, aggregated to monthly counts | [MoH-Malaysia/covid19-public](https://github.com/MoH-Malaysia/covid19-public) (`epidemic/cases_state.csv`) |
| `GE14_cleaned.csv` | Constituency-level GE14 results with Malay population share and urbanisation class | Author's compilation from The Star |


------------------------------------------------------------------------


## Resources

- tidyplots documentation and cheatsheet: <https://tidyplots.org> (cheatsheet: <https://tidyplots.org/tidyplots-cheatsheet-v1.pdf>)
- Engler, J. B. (2025). [doi:[10.1002/imt2.70018](doi:%5B10.1002/imt2.70018){.uri}](https://doi.org/10.1002/imt2.70018)
- Malaysia Ministry of Health open data: <https://github.com/MoH-Malaysia/covid19-public>

## Contact

Associate Professor Dr. Jason Ng · Sunway University · jasonn@sunway.edu.my

## Citation

If you reuse these materials, please cite:

> Ng, J. (2026). *Tidyplots: Data Visualisation Made Simple(R)* [Workshop materials]. R confeRence 2026 Malaysia. https://github.com/jngwj/Tidyplots-Data-Visualisation-Made-SimpleR.git.

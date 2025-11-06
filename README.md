# Climate Resilience & Investment Strategy for Hampshire Sparkling Wine Production

This repository explores whether **French Champagne producers** (specifically the case of Taittinger) should consider **long-term investment in vineyards and sparkling-wine production in Hampshire, UK**. The work evaluates the role of **climate change**, its projected effects on viticulture suitability, and the commercial viability of English sparkling wine as a strategic expansion option.

This work was developed as part of an **independent research exercise at Imperial College London**.  
The project is **archived / paused** — core structure and early-stage analysis are included here, but full production modelling, statistical forecasts, and commercial conclusions were **not fully completed**. Future updates may refine and extend the modeling approach.

---

<br>

## 🎯 Core Question

**Should French Champagne houses invest in long-term sparkling wine operations in Hampshire, UK?**

<br>

## 🧭 Research Strategy

The project frames the investigation as a sequence of data-driven experiments:

| Research Question | Approach |
|---|---|
| Is Hampshire currently suitable for high-quality viticulture? | Climate baseline analysis & grape suitability metrics |
| How will **climate change** affect Hampshire’s viticulture conditions? | Use historical climate data + future climate projections (UKCP18 / CMIP6) |
| Will climate change be **positive, negative, or neutral** for sparkling wine quality and yield? | Temperature band analysis, phenology modelling, frost & heat stress trends |
| How might these changes affect the **commercial wine sector** over the next 50 years? | Economic & competitive landscape review |

Each analytical step follows a standard structure:


<br>

## 📦 Data Sources (Intended / Referenced)

| Dataset | Purpose | Access |
|---|---|---|
| UKCP18 Climate Projections | Future climate scenarios for Hampshire | Free / Open Access |
| ERA5 / CRU Timeseries | Historical climate records | Open Access |
| UK Wine Industry Production Statistics | Sector growth and quality performance indicators | Public / Trade Reports |
| Soil, elevation, and land classification maps | Vineyard suitability mapping | Ordnance Survey / UK Gov Open Data |

*Note:* Not all listed datasets are fully integrated yet — some appear in exploratory code only.

<br>

## 🗂 Repository Structure

```
.hampshire-wine-investment/
    ├── data /
    │   ├── ERA/
    │   │   └── Experiments/
    │   │   │   ├── ClimateIndicatorsTempGDDPrec.grib
    │   │   │   ├── ERA5data.grib
    │   │   │   ├── ERA5data.nc
    │   │   │   ├── ERAtest_subarea_1deg1deg.nc
    │   │   │   ├── ERA5data_new.zip
    │   │   │   └── ERA5data_new/
    │   │   │   │   ├── 01_mean_temperature-reanalysis-monthly-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── 02_growing_degree_days-reanalysis-monthly-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── l1_daily_maximum_temperature-reanalysis-monthly-max-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── l1_daily_maximum_temperature-reanalysis-monthly-mean-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── l1_daily_maximum_temperature-reanalysis-monthly-min-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── l2_daily_minimum_temperature-reanalysis-monthly-max-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   ├── l2_daily_minimum_temperature-reanalysis-monthly-mean-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │   │   │   └── l2_daily_minimum_temperature-reanalysis-monthly-min-grid-1940-2023-v1.0.area-subset.51.5.-5.5.50.0.1.5.nc
    │   │
    │   └── UKCP
    │
    ├── hampshire_wine_investment.ipynb
    │
    └── README.md       # you are here


```


<br>

## 📌 Status

This project is **not currently under active development**.

It is kept here as:

- A reference for others interested in climate impacts on viticulture
- A possible foundation for future deeper modelling and publishing
- Documentation of research methodology as part of academic work

Future extensions may include:

- Vineyard suitability GIS modelling
- CMIP6 ensemble phenology forecasts
- Yield & quality index modelling


<br>

## 🤝 Acknowledgements

This research exercise was initiated as part of graduate study at **Imperial College London**.  
No commercial relationship with Taittinger or any wine producer is implied.




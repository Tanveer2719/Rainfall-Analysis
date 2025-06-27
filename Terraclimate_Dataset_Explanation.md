### 🌾 Bangladesh TerraClimate Dataset (1958–2022)

This dataset comprises **TerraClimate** monthly records for **35 weather stations across Bangladesh** from **January 1958 to December 2022**, resulting in **28,140 observations** and **19 features**. Each record represents climate and environmental data for a specific station and month.

---

#### 📋 Dataset Overview

| Column Name     | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `name`          | Name of the station (e.g., Barisal, Bogra)                                 |
| `longitude`     | Longitude of the station (in decimal degrees)                              |
| `latitude`      | Latitude of the station (in decimal degrees)                               |
| `month`         | Month of the observation (1 = January, ..., 12 = December)                 |
| `year`          | Year of the observation (range: 1958–2022)                                 |
| `aet`           | Actual evapotranspiration (mm)                                              |
| `def`           | Climatic water deficit (mm)                                                 |
| `pdsi`          | Palmer Drought Severity Index (unitless)                                   |
| `pet`           | Potential evapotranspiration (mm)                                           |
| `pr`            | Precipitation (mm)                                                          |
| `ro`            | Runoff (mm)                                                                 |
| `soil`          | Soil moisture (mm)                                                          |
| `srad`          | Downward shortwave solar radiation (W/m²)                                   |
| `swe`           | Snow water equivalent (mm) (usually 0 for Bangladesh)                       |
| `tmmn`          | Minimum temperature (°C * 10)                                                |
| `tmmx`          | Maximum temperature (°C * 10)                                                |
| `vap`           | Vapor pressure (Pa)                                                         |
| `vpd`           | Vapor pressure deficit (Pa)                                                 |
| `vs`            | Wind speed at 10 m above ground (m/s * 10)                                  |

---

#### 🗺️ Geospatial Scope

- **Number of Stations**: 35  
- **Geographic Coverage**: All major regions of Bangladesh  
- **Latitude Range**: ~20.5°N – 26.5°N  
- **Longitude Range**: ~88.0°E – 92.5°E  

---

#### 📊 Data Shape

- **Rows**: 28,140 (35 stations × 12 months × ~67 years)  
- **Columns**: 19  

---


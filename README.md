<!-- Profile README for github.com/mfarmani95 -->
<h1 align="center">Mohammad A. Farmani</h1>
<p align="center"><b>Ph.D. Student, Hydrology & Atmospheric Sciences (University of Arizona)</b></p>

<p align="center">
  <a href="https://mfarmani95.github.io/Mfarmani/index.html"><img alt="Website" src="https://img.shields.io/badge/Website-Home-2ea44f?logo=firefox-browser&logoColor=white"></a>
  <a href="mailto:mohammadalifarmani95@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-blue?logo=gmail&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=CmjfHnIAAAAJ&hl=en"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?logo=google-scholar&logoColor=white"></a>
  <a href="https://www.researchgate.net/profile/Mohammad-Farmani-6/research"><img alt="ResearchGate" src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?logo=researchgate&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/mohammad-farmani-841b2b180/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white"></a>
</p>

### About
I’m a third-year Ph.D. candidate in Hydrology & Atmospheric Sciences (minor in Data Science) at the University of Arizona. I integrate **physical hydrology** with **machine learning** and **differentiable modeling** to improve predictions of soil moisture, evapotranspiration, recharge, and streamflow.

**Recent highlights (2025):**  
- **Soil moisture memory:** first-author study identifying key soil processes controlling memory (HESS 2025).  
- **Precipitation intensity → recharge/TWS:** coauthored **GRL 2025** showing strong impacts in Arizona drylands.  
- **Product evaluation across temperatures:** coauthored **J. Hydrometeorology 2025** comparing IMERG V07/V06 vs. ERA5.  
- **ET with physics-guided ML:** coauthored **J. Hydrology 2025** (DNN-enhanced Penman–Monteith).

**Focus areas**
- **Hydrologic & land-surface modeling:** Noah-MP and RAPID (infiltration, runoff, baseflow, soil moisture dynamics).  
- **Differentiable hydrology & ML:** PyTorch implementations for GPU-accelerated parameter optimization and hybrid physics–ML.  
- **Extremes & recharge:** linking precipitation intensity to groundwater recharge and terrestrial water storage.  
- **Data systems & reproducible pipelines:** Python/xarray/geopandas, HPC, and SQL for scalable, transparent workflows.  
- **Urban/flood applications:** SWMM/HEC tools for stormwater and resilience analyses.

I like bridging theory and practice—building tools that help answer real water-resources questions, mentoring peers, and contributing service/leadership (e.g., El Día Student Symposium).

---

## Research Experience

**Graduate Research Assistant, University of Arizona — Tucson, AZ, USA**  
- **Lead author (HESS 2025):** identified **key soil hydrological processes** governing soil moisture memory; designed experiments and analysis with Noah-MP.  
- **Coauthor (GRL 2025):** quantified how **precipitation intensity** drives **groundwater recharge** and **TWS change** in Arizona drylands.  
- **Coauthor (Journal of Hydrometeorology 2025):** evaluated **IMERG V07/V06 vs. ERA5** across **near-surface temperature regimes**.  
- **Coauthor (Journal of Hydrology 2025):** developed a **DNN-enhanced Penman–Monteith** framework for improved **evapotranspiration** estimation.
- Advanced **Noah-MP** process representation and **parameter optimization** using differentiable hydrology (PyTorch; GPU).  
- Implemented **river-discharge routing** with **RAPID**; analyzed baseflow generation and streamflow prediction skill.  
- Built **gauge-sampled vs. gridded** precipitation comparison workflows (AORC, NLDAS2, CONUS404, IMERG) with xarray/rioxarray.  
- Developed **reproducible pipelines** on HPC for large-scale NetCDF processing, calibration, and evaluation.
- Conceptual modeling of streamflow generation processes for the Leaf River basin

**Graduate Research Assistant, Tarbiat Modares University — Tehran, Iran**  
- Downscaling low-resolution GCM data with machine learning and deep learning  
- Temporal disaggregation of precipitation data with the KNN algorithm  
- Extracted hydrological characteristics of sub-catchments in the Tehran basin using DEMs (ArcGIS)  
- Hydraulic modeling of urban flooding in Tehran’s drainage system with SWMM and HEC-RAS  
- Extreme value analysis of rainfall events to create IDF curves  
- Simulated urban floods in SWMM using MATLAB  
- System dynamics analysis of crisis management with VENSIM (Zayandeh-Rud River Basin, Isfahan)  
- Hydrological flood modeling in the Tehran basin with ArcGIS and HEC-HMS

---

## Publications & Preprints

**Peer-reviewed**
- Farmani, M. A., Behrangi, A., Gupta, A., Tavakoly, A., Geheran, M., & Niu, G.-Y. (2025). *Do land models miss key soil hydrological processes controlling soil moisture memory?* **Hydrology and Earth System Sciences**, 29, 547–566. https://doi.org/10.5194/hess-29-547-2025  
- Agnihotri, J., Behrangi, A., Tavakoly, A., Geheran, M., **Farmani, M. A.**, & Niu, G.-Y. (2023). Higher frozen soil permeability represented in a hydrological model improves spring streamflow prediction from river basin to continental scales. **Water Resources Research**, 59(4), e2022WR033075.
- **The Strong Impact of Precipitation Intensity on Groundwater Recharge and Terrestrial Water Storage Change in Arizona, a Typical Dryland.**  
  Y. Qiu, J. S. Famiglietti, A. Behrangi, **M. A. Farmani**, H. Yousefi Sohi, A. Gupta, *et al.* **Geophysical Research Letters**, 52(14), e2025GL114747 (2025). https://doi.org/10.1029/2025GL114747  
- **How Do IMERG V07, IMERG V06, and ERA5 Precipitation Products Perform over Snow–Ice-Free and Snow–Ice-Covered Surfaces at a Range of Near-Surface Temperatures?**  
  H. Yousefi Sohi, **M. A. Farmani**, A. Behrangi. **Journal of Hydrometeorology**, 26(7), 837–855 (2025). https://doi.org/10.1175/JHM-D-24-0110.1  
- **Improved Evapotranspiration Estimation Using the Penman–Monteith Equation with a Deep Learning (DNN) Model Over the Dry Southwestern US: Comparison with ECOSTRESS, MODIS, and OpenET.**  
  M. Jawad, A. Behrangi, **M. A. Farmani**, Y. Qiu, H. Y. Sohi, A. Gupta, G.-Y. Niu. **Journal of Hydrology**, 133460 (2025). *(Article in press)*  
- **Do land models miss key soil hydrological processes controlling soil moisture memory?**  
  **M. A. Farmani**, A. Behrangi, A. Gupta, A. Tavakoly, M. Geheran, G.-Y. Niu. **Hydrology and Earth System Sciences**, 29, 547–566 (2025). https://doi.org/10.5194/hess-29-547-2025
- **Farmani, M. A.**, Tavakoly, A. A., Behrangi, A., *et al.* (2024). Improving Streamflow Predictions in the Arid Southwestern United States Through Understanding of Baseflow Generation Mechanisms. *ESS Open Archive*. https://doi.org/10.22541/essoar.173272456.69006273/v1  
- Niu, G.-Y., Fang, Y., Alves Meira Neto, A., Guo, B., Zhang, X.-Y., **Farmani, M.**, Behrangi, A., & Zeng, X. (2024). Representing Preferential Flow through Variably-Saturated Soils with Surface Ponding in a Large-Scale Land Surface Model over the Conterminous US. *ESS Open Archive*. https://doi.org/10.22541/essoar.172286649.90332939/v1  
- Yousefi Sohi, H., **Farmani, M. A.**, & Behrangi, A. (2024). How do IMERG V07, IMERG V06, and ERA5 Precipitation Products Perform Over Snow-ice-free and Snow-ice-covered Surfaces at a Range of Near-Surface Temperatures? *ESS Open Archive*. https://doi.org/10.22541/essoar.172675931.16404474/v1  
- Jawad, M., Behrangi, A., **Farmani, M.**, Qiu, Y., Yousefi, H., Gupta, A., & Niu, G.-Y. Improved Evapotranspiration Estimation Using the Penman–Monteith Equation with a Deep Learning (DNN) Model Over the Dry Southwestern US: Comparison with ECOSTRESS, MODIS, and OpenET. *SSRN*. https://ssrn.com/abstract=5026281 • https://doi.org/10.2139/ssrn.5026281

---

## Conference Presentations
- Improving Streamflow Predictions in the Dry Southwestern United States Through Understanding of Baseflow Generation Mechanisms. **AGU 2024**  
- How do IMERG V07, IMERG V06, and ERA5 Precipitation Products Perform Over Snow-ice-free and Snow-ice-covered Surfaces? **AGU 2024**  
- The Significant Impact of Precipitation Intensity on Natural Groundwater Recharge and Terrestrial Water Storage Change in Arid Regions. **AGU 2024** (Qiu, Niu, Behrangi, Famiglietti, **Farmani**, Gupta, *et al.*)  
- Implementing the ML-based Van Genuchten parameterization in the NextGen Framework for improved streamflow prediction. **AGU 2024** (Gupta, Behrangi, **Farmani**, Niu)  
- What Are the Key Soil Hydrological Processes to Control Soil Moisture Memory? **CMWR 2024**  
- Representing Preferential Flow through Variably Saturated Soils with Surface Ponding in Noah-MP. **AGU 2023**, H11G-1343 (Niu, Fang, Alves Meira Neto, Guo, **Farmani**, Behrangi)  
- Impact of Vegetation Dynamics on Hydrological Fluxes using Noah-MP Coupled to NextGen Modeling Framework: A Case Study of High-resolution Hydrological Simulations over California. **AGU 2023**, H31V-1798 (Gupta, Behrangi, **Farmani**, Niu)

---

## Awards & Honors
- 🏅 **AHS Academic Scholarship** (2025)  
- 🥈 **CAP Award for Water Research — 2nd place**
- 🏅 **CIROH HydroLearn Fellowship** (2025)  
- 🥈 **Second place**, Groundwater Student Contest, **AGU24** (2024)  
- 🎖️ **John W. and Margaret Harshbarger Fellowship** (2024)  
- 🎖️ **Roots for Resilience Research Fellowship**, Data Science Institute, University of Arizona (Fall 2023)  
- 🎖️ **Best Oral Presentation**, El Día Conference, University of Arizona (March 2023)  
- 🎖️ **Hydrologist Scholarship**, U.S. Army Corps of Engineers – ERDC CHL (May 2023 – Present)  



> Full portfolio, publications, talks, and CV: **https://mfarmani95.github.io**

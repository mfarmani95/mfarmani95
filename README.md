<!-- Profile README for github.com/mfarmani95 -->
<h1 align="center">Moe Farmani</h1>
<p align="center"><b>Ph.D. Candidate | Hydrology & Atmospheric Sciences</b></p>
<p align="center"><i>University of Arizona | Integrating Physics, Machine Learning & Data Science</i></p>

<p align="center">
  <a href="https://mfarmani95.github.io/Mfarmani/index.html"><img alt="Website" src="https://img.shields.io/badge/Portfolio-Website-2ea44f?style=for-the-badge&logo=firefox-browser&logoColor=white"></a>
  <a href="mailto:mohammadalifarmani95@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-blue?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=CmjfHnIAAAAJ&hl=en"><img alt="Google Scholar" src="https://img.shields.io/badge/Scholar-Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white"></a>
  <a href="https://www.researchgate.net/profile/Mohammad-Farmani-6/research"><img alt="ResearchGate" src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/mohammad-a-farmani-841b2b180/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

---

## 🌍 About Me

I am a Ph.D. candidate in Hydrology and Atmospheric Sciences at the University of Arizona, with research interests spanning physical hydrology, geospatial data science, and machine learning.

My experience includes large-scale physical and hydrologic modeling with **Noah-MP** and **RAPID**, along with geospatial analysis and scientific computing using **xarray, GDAL, GIS, and Python**. I work extensively with large environmental datasets, hydrologic workflows, and reproducible model evaluation pipelines.

I also **develop deep learning, hybrid physics–ML, and distributed GPU-based workflows** for hydrologic prediction. My current focus is on building **data pipelines** and modeling frameworks in **PyTorch**, including translating Fortran-based models such as **Noah-MP** into **GPU-enabled, deep-learning-ready** implementations that can be coupled with neural networks.

I am particularly interested in building scalable and interpretable systems that unify physical models, geospatial data, and modern machine learning for water-resources applications.

---

## 💡 Research Directions

### 🔬 **Hydrologic & Land-Surface Modeling**
- **Noah-MP & RAPID** models for infiltration, runoff, baseflow, and soil moisture dynamics
- Process-based model development, calibration, and uncertainty quantification
- High-performance computing (HPC) implementations for large-scale simulations
- Snow-hydrology interactions and subsurface water dynamics

### 🤖 **Differentiable Hydrology & Machine Learning**
- PyTorch implementations for GPU-accelerated parameter optimization
- Hybrid physics-guided + machine learning systems
- Differentiable modeling enabling automatic differentiation through hydrology
- Neural networks with physical constraints and conservation laws

### 🌊 **Streamflow Forecasting & Prediction**
- Deep learning approaches: LSTMs, Transformers, attention mechanisms
- Physics-informed neural networks (PINNs) for process representation
- Transfer learning for ungauged basins
- Multi-step ahead forecasting with uncertainty quantification

### 📊 **Data Systems & Reproducible Workflows**
- Python, xarray, geopandas for scalable geospatial analysis
- SQL databases and cloud computing for big hydrology
- HPC workflows and containerization (Docker)
- Open science practices and reproducible pipelines

### 💧 **Water Resources Applications**
- Linking precipitation intensity to groundwater recharge and terrestrial water storage (TWS)
- Extremes analysis (droughts, floods) in water-limited environments
- Urban hydrology and stormwater management (SWMM, HEC-RAS)
- Climate adaptation and water security in drylands

---

## 🚀 Current Projects

### 🔴 **Noah-MP-PyTorch: Vectorized Land Surface Modeling with GNN Routing**
*Status: In Development (Private) | Release: Q3 2026*

A fully differentiable, GPU-accelerated implementation of Noah-MP coupled with Graph Neural Network routing for scalable hydrologic modeling.

**Key Features:**
- ⚡ **50x+ speedup** over traditional Noah-MP via GPU vectorization
- 🔄 **Fully differentiable** – automatic differentiation through entire model
- 🧠 **Graph Neural Networks** for learnable streamflow routing
- 🔗 **Hybrid physics-ML** – seamless integration with machine learning
- 📈 **Scalable** across 1000s of catchments simultaneously

**Technical Stack:** PyTorch, CUDA, XLA, Physics-Guided ML

**Early Access:** Available for research collaborations

---

### 🟢 **Streamflow-DL: Deep Learning for Streamflow Prediction**
*Status: Active & Available*

Deep learning approaches for streamflow forecasting using sequence models (LSTM, Transformers) with physics-guided training.

**Key Capabilities:**
- 📊 **Benchmark Performance:** NSE = 0.81 on CAMELS (531 basins)
- 🧠 **Models:** LSTM, Transformer, hybrid physics-ML architectures
- 📚 **Datasets:** CAMELS, USGS, GRDC
- 🎯 **Applications:** 1–30 day forecasting, ungauged basins, extremes
- ⚙️ **Production-ready:** Configurable training pipelines, evaluation metrics

**Tech Stack:** PyTorch, Transformers, Transfer Learning, Physical Loss Functions

**[Repository]([https://github.com/mfarmani95/streamflow-dl](https://github.com/mfarmani95/Streamflow_Prediction/tree/main)) | [Documentation]()**

---

### 🟡 **Coffee Suitability & Deforestation Analysis**
*Status: Complete & Production-Ready*

A YAML-driven geospatial analysis pipeline for rapid assessment of coffee suitability and forest loss over user-defined regions of interest. Integrates multi-source satellite data with automated preprocessing and analysis workflows.

**Pipeline Capabilities:**
- 🌍 **Multi-source Data Integration:** CHIRPS rainfall, MODIS NDVI, SMAP soil moisture, Hansen forest loss
- 🔄 **Automated Preprocessing:** Harmonize disparate datasets to shared monthly grid (NetCDF)
- ☕ **Suitability Analysis:** Apply science-based thresholds for NDVI, rainfall, and soil moisture
- 📍 **Forest-Loss Detection:** Quantify overlap between suitable coffee regions and deforestation signals
- 📊 **Rich Outputs:** Time-series plots, spatial maps, CSV tables, NetCDF datasets, summary reports
- ⚙️ **Configuration-Driven:** YAML configs for reproducible, parameterizable workflows

**Key Features:**
- 🎯 Offline synthetic demo (no credentials required for first run)
- 🛰️ Real-data workflows with MODIS/SMAP via NASA Earthaccess
- 🔍 Data validation and quality checks for HDF5 corruption
- 📈 Extensible pipeline supporting custom AOI and time windows
- 📦 Standardized NetCDF intermediate format for reproducibility

**Tech Stack:** Python, Rasterio, Xarray, NetCDF, YAML, Google Earth Engine, NASA Earthdata API

**[Repository]([[https://github.com/mfarmani95/streamflow-dl](https://github.com/mfarmani95/Streamflow_Prediction/tree/main](https://github.com/mfarmani95/coffee_analysis))) | [Documentation]()**
---

## 📚 Research Highlights

### **2025 Publications**

| Publication | Topic | Journal | Status |
|---|---|---|---|
| **First-author** | Streamflow Prediction via Enhanced Baseflow Estimation | *Water Resources Research* | ✅ Published |
| **First-author** | Soil Moisture Memory & Process Controls | *Hydrology and Earth System Sciences* | ✅ Published |
| **Co-authored** | Precipitation Intensity → Recharge/TWS in Arizona Drylands | *Geophysical Research Letters* | ✅ Published |
| **Co-authored** | IMERG V07/V06 vs. ERA5 Product Evaluation | *J. Hydrometeorology* | ✅ Published |
| **Co-authored** | Physics-Guided ML for Evapotranspiration | *J. Hydrology* | ✅ Published |

**➜ Full publication list:** [Google Scholar Profile](https://scholar.google.com/citations?user=CmjfHnIAAAAJ&hl=en)

---

## 💻 Technical Expertise

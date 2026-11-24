# indraliauwprior.github.io

# Indra Samudra Liauw-Prior

**Spatial Development Economics**

------------------------------------------------------------------------

### Professional Biography

I am a recent MSc Graduate of Local Economic Development at the London School of Economics (LSE). My dissertation evaluated the effects of the nickel export ban in Indonesia that began in 2014, utilising R, GIS, and remote-sensing data. This portfolio highlights some of the passion projects and research questions that interest me. I employ economic theories combined with geographical data science to demonstrate economic geographical realities and analyse policy.

[**Request Briefing**](indraliauwprior@gmail.com) \| [**LinkedIn**](www.linkedin.com/in/indra-liauw-prior-1a2b3c) \| [**Advisory Portfolio**](indraliauwprior.github.io)

------------------------------------------------------------------------

### Core Areas of Interest

- **Spatial Econometrics & Forecasting:** Empirical modeling of trade, labor, and demographic flows utilizing advanced gravity models and spatial autoregressive frameworks.
- **Infrastructure & Network Analytics:** Origin-Destination (O/D) matrix calibration, transport network impedance assessments, and catchment optimization.
- **Analytics Supervision & Audit:** Implementation of rigorous code-validation pipelines, geometric reference system data controls, and boundary condition auditing.

------------------------------------------------------------------------

### Exisiting Portfolio Projects

#### 📑 Nickel Mining In Indonesia

- **Why Nickel?** The industry has become essential to Indonesia's economic development strategy as they have implemented export restrictions and fostered downstream industrial development.
- **Why Spatial Analysis?** There is debate over whether these economic benefits are enabling sustained material growth for nickel regions. Academic critiques have labelled the industry as forming a "nationalist enclave" strategy (Warburton, 2023). Analysis of the economic geographic realities contributes quantitative evidence to this debate.
- **Data and Methods** Granular time-series economic data is scarce for this region in Indonesia. Remote-sensing satellite datasets where chosen to act as a proxy for economic data, nightlight acted as the main dependent variable. 
All data was sourced through the internet and a full reference list can be found in the research page below.Remote-sensing data was sourced through Google Earth Engine (GEE), then cleaned in ArcGIS and R code, analysis was finally completed in R.
Regression analysis used distance from industrial sites to determine effects on economic output. The main result indicator utilised a difference in difference approach while a range of logical forms and specifications, further strengthened findings.
- **Outcomes** Results indicate that with each doubling distance from a smelting site there was a 67% lower chance of luminosity and 11% less probability of built development. The staggered difference in difference results further demonstrate the direct relation between new smelters and an increase in nightlight output.
- **Deliverables** [Interactive Dashboard](LINK) / [Executive Briefing Paper (PDF)](LINK)

#### 📑 Has the Sydney new Metro M1 improved accessiblity or just caused house prices to increase?

- **The Mandate:** Optimize site selection for a multi-million dollar retail development portfolio while minimizing internal market cannibalization.
- **The Approach:** Designed a spatial interaction framework in Python (`PySAL`, `GeoPandas`) utilizing Huff’s Probability Surfaces to map competing catchments across localized demographics.
- **The Outcome:** Isolated three optimal spatial coordinates, capturing an estimated **\$5.4M in latent market demand** while successfully keeping asset-to-asset cannibalization below a strict 2.5% threshold.
- **Deliverables:** [Market Probability Model](LINK)

------------------------------------------------------------------------

### Methodological Framework & Guardrails

To ensure econometric integrity when deploying advanced spatial analytics, my models adhere to a strict data-auditing pipeline:

1.  **Geometric Validation:** Continuous auditing of Coordinate Reference Systems (CRS) to guarantee zero spatial distance distortions during distance calculations.
2.  **Boundary Condition Controls:** Custom configuration of spatial weight matrices tailored specifically to regional topographical and regulatory boundaries.
3.  **Zero-Flow Processing:** Integration of Poisson Pseudo-Maximum Likelihood (PPML) estimators to accurately handle empty spatial interactions without biasing macro-level indicators.

------------------------------------------------------------------------

*Document updated: October 2026. Data and methodologies audited for institutional compliance.*

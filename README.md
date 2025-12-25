# environmental-risk-esg-gee
Environmental Risk Mapping for Sustainable Finance Using Satellite Data (Google Earth Engine)

---

# Environmental Risk Mapping for Sustainable Finance Using Satellite Data

## Overview

This project demonstrates a **basic, satellite-based approach to Environmental (E) risk assessment** for **ESG and sustainable finance**. Using **Google Earth Engine**, the project maps environmental stress indicators and combines them into a simple environmental risk index that can support ESG-aware investment and lending decisions.

The goal is to show how **objective, geospatial climate data** can complement or improve traditional, disclosure-based ESG analysis.

---

## Why This Matters for ESG & Sustainable Finance

Traditional ESG scores often rely on **self-reported and lagged data**.
This project uses **satellite observations** to provide:

* Location-specific environmental risk
* Forward-looking physical climate exposure
* Visual evidence of environmental stress

Such approaches are increasingly relevant for:

* Sustainable investing
* Climate-aware credit risk
* ESG due diligence
* Climate risk screening

---

## Data & Technology

* **Platform:** Google Earth Engine
* **Programming:** JavaScript (Earth Engine Code Editor)
* **Satellite Data (MODIS):**

  * NDVI (Vegetation Health)
  * Land Surface Temperature (Heat Stress)

---

## Methodology (Simple & Transparent)

### 1. Vegetation Health (NDVI)

* NDVI measures land greenness and vegetation health.
* Lower NDVI values indicate environmental stress.

### 2. Heat Stress (Land Surface Temperature)

* Higher temperatures indicate increased climate and operational risk.
* Heat stress affects productivity, infrastructure, and asset resilience.

### 3. Environmental Risk Index

Both indicators are normalized and combined:

* **Higher temperature → higher risk**
* **Lower vegetation → higher risk**

The resulting map highlights **areas with elevated environmental risk** relevant for sustainable finance.

---

## Firms / Banks Overlay

Sample firm and bank locations are overlaid on the environmental risk map to illustrate how **asset location** affects climate-related exposure.

This demonstrates how investors or lenders can:

* Identify assets in high-risk zones
* Compare exposure across locations
* Support ESG-aware capital allocation

---

## Outputs

The `outputs/` folder contains exported maps:

* NDVI (Vegetation Health)
* Temperature (Heat Stress)
* Composite Environmental Risk Map

These visual outputs can be used in:

* ESG reports
* Presentations
* Blogs or policy notes

---

## How to Reproduce

1. Open **Google Earth Engine Code Editor**
2. Copy the script from `gee_code.js`
3. Run the script step-by-step
4. Export maps using `Export.image.toDrive()`

---

## Key Insight

> Satellite-based environmental indicators provide an objective, location-specific view of climate risk that is highly relevant for ESG and sustainable finance decision-making.

---

## Disclaimer

This is a **basic demonstration project** intended for learning and illustration.
It is not investment advice and does not replace full ESG or climate risk models.

---




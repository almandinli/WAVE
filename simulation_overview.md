# 🌍 Flood-to-Disease Risk Simulation: South-Eastern Europe Pilot

## 🔹 Input Data Layers
- 🌧️ **Satellite Rainfall Data**
  - Source: Copernicus, GloFAS
- 🗺️ **Topography (DEM)**
  - To simulate runoff directions
- 🌿 **Land Cover**
  - To estimate runoff intensity and infiltration
- 💧 **Groundwater & Well Data**
  - Well depth, location, and protection status
- 🏥 **Hospital/Health Data**
  - Disease reports (if available, for model training/validation)

---

## 🔄 Processing Steps
1. **Runoff Routing Model**
   - Simulates surface water flow during flood events
2. **Infiltration Estimation**
   - Calculates contamination risk based on permeability and slope
3. **Contamination Risk Mapping**
   - Identifies wells and areas with potential for pathogen entry

---

## 📤 Output
- 🗺️ **Risk Maps**
  - Spatial output showing vulnerable zones
- ⚠️ **Advisory Flags**
  - Recommends UV filtration deployment or alerts
- 📊 *(Optional)* **Dashboard**
  - Future integration: contamination index, hospital reports

---

## ✅ Purpose
> Efficiently allocate resources like **UV filtration** to prevent disease outbreaks and reduce pressure on public health systems.

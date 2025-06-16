# Automating Urban Parameter Calculations: GRZ Workflows in Hamburg

This repository contains selected scripts and methods developed for a Master's thesis at **Technische Hochschule Ostwestfalen-Lippe**. The project explores and compares two computational workflows—PostGIS and QGIS—for calculating the Building Coverage Ratio (GRZ, Grundflächenzahl) based on cadastral data (ALKIS) for the city of Hamburg.

📄 **Full thesis title**:  
*Automating Urban Parameter Calculations: A Comparative Study of GIS Workflows and Spatial Query Methods for Large-Scale Urban Analysis.*

👤 **Author**: Juan Hernández  
🏛️ **Institution**: Technische Hochschule Ostwestfalen-Lippe  
📅 **Year**: 2025

---

## 📦 Repository Contents

```bash
/sql/           → SQL queries for GRZ calculation using PostGIS  
/python/        → QGIS-based automation scripts (Python)  
/docs/          → Licensing notes, legal references, and metadata  
/examples/      → Workflow diagrams or screenshots  
```

---

## 📌 Project Summary

This research presents an automated method to compute parcel-based GRZ values using official cadastral data (ALKIS) for Hamburg. It evaluates two workflows:
1. QGIS-based semi-automated workflow (geometry-based + Python scripting)
2. PostGIS-based fully automated workflow (SQL-based spatial queries)

Core topics include:
- Geometry validation and data cleaning
- Handling overlapping structures
- Calculating GRZ_main and GRZ_aux
- Identifying underutilised parcels and spatial inconsistencies

---

## 🧾 License

- **Code (SQL & Python)**: Released under the MIT License  
- **Documentation & diagrams**: Released under CC-BY 4.0, unless otherwise stated

---

## ⚠️ Data Usage Restrictions

Due to licensing restrictions from the Landesbetrieb Immobilienmanagement und Grundvermögen (LIG), raw ALKIS datasets cannot be published. This repository only includes:
- Derived scripts and reproducible workflows
- Documentation that allows replication using publicly available or equivalent cadastral data

Please respect local licensing terms when sourcing or using spatial data.

---

## 🔁 Reproducibility

Tested environments:
- QGIS: Version 3.28+
- PostgreSQL/PostGIS: PostgreSQL 15 with PostGIS 3.3
- Coordinate System: EPSG:25832 (ETRS89 / UTM zone 32N)

---

## 📚 Citation

If you use or adapt these materials, please cite:

> Hernández, Juan (2025). *Automating Urban Parameter Calculations: A Comparative Study of GIS Workflows and Spatial Query Methods for Large-Scale Urban Analysis*. Master’s Thesis, Technische Hochschule Ostwestfalen-Lippe.

---

## 📫 Contact

For academic use, feedback, or collaboration inquiries:  
📧 juan.hernandez@hcu-hamburg.de

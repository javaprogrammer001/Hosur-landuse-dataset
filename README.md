Overview

This dataset contains environmental indices and ecological quality measures for Housur, India, based on remote sensing data. The dataset spans three time points: 2004, 2014, and 2024, allowing temporal analysis of land use and ecological changes. The data includes RSEI (Remote Sensing Ecological Index) values and PCA (Principal Component Analysis) results derived from key environmental indicators: LST, NDVI, WET, and NDBI.

1. RSEI Data

RSEI (Remote Sensing Ecological Index) combines multiple environmental indicators into a single value representing ecological quality.
| Column      | Description                                                                |
| ----------- | -------------------------------------------------------------------------- |
| **pointid** | Unique identifier for each spatial location in Housur.                     |
| **LST**     | Land Surface Temperature (higher = warmer/urban heat areas).               |
| **NDVI**    | Normalized Difference Vegetation Index (higher = more vegetation).         |
| **WET**     | Wetness index (higher = more soil moisture or water content).              |
| **NDBI**    | Normalized Difference Built-up Index (higher = more urbanization).         |
| **RSEI**    | Remote Sensing Ecological Index (0–1; higher = better ecological quality). |

2. PCA Data

PCA (Principal Component Analysis) is used to reduce the dimensionality of environmental indicators and identify the main drivers of ecological variation.

| Column / Section          | Description                                                                                |
| ------------------------- | ------------------------------------------------------------------------------------------ |
| **PC1, PC2, PC3, PC4**    | Principal components capturing variance in LST, NDVI, WET, and NDBI.                       |
| **Eigenvalues**           | Variance explained by each principal component.                                            |
| **Percent of Variance**   | Percentage of total variance explained by each PC.                                         |
| **Eigenvectors**          | Contribution of each original indicator to each PC.                                        |
| **Weights / PC1 Weights** | Specific contribution of LST, NDVI, WET, and NDBI to PC1, which is used to calculate RSEI. |

Temporal Coverage

2004 – Baseline ecological assessment.

2014 – Mid-term assessment, showing trends in land use and ecological change.

2024 – Most recent assessment (projected or current data), allowing analysis of ongoing urbanization and ecological dynamics.

Usage Notes

RSEI Interpretation: Higher values indicate better ecological quality (more vegetation, moisture, and less urbanization).

PCA Interpretation: PC1 captures the largest variance in ecological quality; subsequent PCs explain smaller contributions.

The dataset can be used for environmental monitoring, urban planning, ecological studies, and temporal change detection in Housur.

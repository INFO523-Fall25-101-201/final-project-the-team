# Data
- **kaggle_Discovery_statistics**: This dataset was downloaded from Kaggle NASA NEO (Near-Earth Object) Dataset. This dataset contains data on NEOs to include name, designation, absolute magnitudes, estimated diameters, and hazard assessments. sourced from NASA.  

# Codebook for [kaggle_Discovery_statistics] Dataset
Jupyter Notebook

## Variable Names and Descriptions:

-   **Designation**     : Designation of NEO object
-   **Discovery Date**  : Date of Discovery
-   **H (mag)**         : Absolute Magnitude
-   **MOID (au)**       : Minimum Orbit Intersection Distance with Earth
-   **q (au)**          : perihelion distance
-   **Q (au)**          : aphelion distance
-   **period (yr)**     : Orbital Period (one full rotation)
-   **i (deg)**         : Orbital Inclination, tilt of orbital plane relative to earch in degrees
-   **PHA**             : Potentially hazardous (target variable)
-   **Orbit Class**     : Near Earth orbital class *

*
| Orbit Class             | Description                                | Key Orbital Traits        |
| ----------------------- | ------------------------------------------ | ------------------------- |
| **AMO (Amor)**          | Approaches but doesn’t cross Earth’s orbit | 1.017 AU < q < 1.3 AU     |
| **APO (Apollo)**        | Crosses Earth’s orbit, long-period orbit   | a > 1 AU and q < 1.017 AU |
| **ATE (Aten)**          | Crosses Earth’s orbit, short-period orbit  | a < 1 AU and Q > 0.983 AU |
| **IEO (Atira/Apohele)** | Orbit entirely inside Earth’s              | Q < 0.983 AU              |

## Data Types:

-   **Designation**     : object
-   **Discovery Date**  : object
-   **H (mag)**         : float64
-   **MOID (au)**       : float64
-   **q**               : float64
-   **Q**               : float64
-   **period (yr)**     : float64
-   **i (deg)**         : float64
-   **PHA**             : Object
-   **Orbit Class**     : Object 




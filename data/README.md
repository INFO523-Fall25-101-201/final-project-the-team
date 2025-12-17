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
|  Group  |  Definition  |  Description  |
|:--------|:------------:|:--------------|
| NECs    | q<1.3au, P<200yrs  |  Near-Earth Comets |
| NEAs    | q<1.3au     |  Near-Earth Asteroids |
| Atiras | a<1.0 au, Q<0.983 au | NEAs whose orbits are contained entirely with the orbit of the Earth (named after asteroid 163693 Atira) |
| Atens  | a<1.0 au, Q>0.983 au | Earth-crossing NEAs with semi-major axes smaller than Earth's (named after asteroid 2062 Aten) |
| Apollos | a>1.0 au, q<1.017 au | Earth-crossing NEAs with semi-major axes larger than Earth's (named after asteroid 1862 Apollo) |
| Amors  | a>1.0 au, 1.017<q<1.3 au | Earth-approaching NEA's with orbits exterior to Earth's but interior to Mars' ( named aftger asteroid 1221 Amor) |
| PHAs   | MOID<=0.05 au, H<=22.0  | Potentially Hazardous Asteroids: NEAs whose minimum Orbit Interestion Distance (MOID) with the Earth is 0.05 au or less and whose absolute magnitude (H) is 22.0 or brighter |  

(q = perihelion distance, Q = aphelion distance, a = semi-major axis)

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




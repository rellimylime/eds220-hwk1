# Exploring Environmental Datasets with Pandas: Coral Reef Diversity and Global Earthquakes

## About

This repository contains data analysis notebooks examining patterns in coral reef diversity and global seismic activity using fundamental data science techniques. The project analyzes coral cover and genera distribution across Western Indian Ocean reef environments, and explores magnitude, location, and depth patterns of earthquakes recorded globally in 2014.

The project demonstrates:
- Data loading and initial exploration with pandas
- DataFrame subsetting and filtering techniques
- Multi-condition data selection and boolean indexing
- Missing data identification and handling
- Statistical summarization of environmental datasets
- Visualization techniques including histograms, bar charts, and geospatial scatter plots
- Reproducible data science workflow practices

This work was completed as part of EDS 220 - Working with Environmental Datasets in the UCSB Master of Environmental Data Science program.

## Repository Structure
eds220-hwk1/
│
├── task2/                                    # Coral diversity analysis
│   ├── hwk1-task2-corals-Miller.ipynb        # Coral diversity analysis notebook
│   ├── data/                                 # Coral dataset and test data
│   │   └── coral_data.csv                    
│   └── tests/                                # Otter grader test files
│
├── task3/                                    # Earthquake data analysis
│   ├── hwk1-task3-earthquakes-Miller.ipynb   # Earthquake analysis notebook
│   ├── data/                                 # Earthquake dataset and test data
│   │   └── earthquake_data.csv               
│   └── tests/                                # Otter grader test files
│
├── README.md                                 # This file
└── License.txt                               # Repository license

## Data

### Data Sources

**Western Indian Ocean Coral Diversity**
Rapid assessment survey data on coral cover and number of genera in the Western Indian Ocean, collected to sample coral bleaching events. The dataset includes reef characteristics, environmental conditions (SST, pH, salinity), and observer metadata across 575 observations spanning 1998-2022.

**USGS Earthquake Database**
Seismic event records from 2014 maintained by the United States Geological Survey. The dataset contains 120,108 total seismic events with spatial information (latitude, longitude, depth), magnitude measurements, timing, and descriptive location data.

### Data Access

The datasets used in this analysis are **included** in this repository within the respective `task2/data/` and `task3/data/` directories for analysis purposes.

**Original data sources:**
- **Coral Diversity**: Available from the Knowledge Network for Biocomplexity (KNB) at https://doi.org/10.5063/F1K35S3H
- **Earthquake Data**: Current earthquake data can be accessed through the USGS Earthquake Search interface at https://earthquake.usgs.gov/earthquakes/search/

## Requirements

This analysis requires Python 3.x with the following packages:
- `pandas` - Tabular data manipulation and analysis
- `matplotlib` - Data visualization
- `otter-grader` - Automated testing and grading

## References

McClanahan, T. (2023). *Western Indian Ocean Coral Diversity* [Data set]. Knowledge Network for Biocomplexity. https://doi.org/10.5063/F1K35S3H

U.S. Geological Survey. (2014). *USGS Earthquake Database* [Data set]. Retrieved from https://earthquake.usgs.gov/earthquakes/search/

Abernathey, R., & Key, K. (2021). *Earth and Environmental Data Science*. https://earth-env-data-science.github.io/intro.html

Wingate, C. (2024). *EDS 220: Working with environmental datasets* [Course materials]. Master of Environmental Data Science, Bren School of Environmental Science & Management, University of California, Santa Barbara. https://meds-eds-220.github.io/MEDS-eds-220-course/

## License

This project is licensed under the terms included in the License.txt file.

---

*This project is part of the curriculum for the Master of Environmental Data Science program at the Bren School of Environmental Science & Management, UC Santa Barbara.*
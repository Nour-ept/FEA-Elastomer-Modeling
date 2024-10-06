# FEA Elastomer Modeling

## Project Overview

This project explores the **modeling of elastomer materials under uniaxial stress** using non-linear Finite Element Analysis (FEA). Elastomers exhibit non-linear behavior when deformed, making accurate material modeling essential for engineering applications. The project aims to assess different hyperelastic models to identify the best one for capturing the stress-strain relationship in elastomers.

The study evaluates hyperelastic models like:
- Neo-Hookean
- Mooney-Rivlin
- Ogden (3-term)

The **Ogden 3-term model** was found to provide the most precise predictions of how elastomers deform under uniaxial stress.

## Technologies Used
- **MSC Marc** for FEA simulations
- **Python** for data analysis and visualization
- **Git** for version control

## Getting Started

### Prerequisites
To run the simulations and follow the analysis, you will need:
- MSC Marc software for Finite Element Analysis
- Python for plotting and analysis of results (optional)

### How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/YourUsername/FEA-Elastomer-Modeling.git
   cd FEA-Elastomer-Modeling
2. Open the project files in MSC Marc to review the model setup and run simulations. The README.md and associated files describe the process of model fitting using uniaxial data.

3. The uniaxial test data and simulation results are included for reference and further analysis.

### Project Files
- MSC_Marc_Simulation_Files/ - All MSC Marc files for the simulations.
- Python_Scripts/ - Python scripts for analyzing stress-strain data and fitting models.
- Internship_Report.pdf - The detailed internship report for this project.
### Report and Documentation
For more details about the project, including the theoretical background and results, refer to the Internship Report:

- [Internship Report - Modeling of Elastomer Material under Uniaxial Stress](Internship Report.pdf)
### License
This project is licensed under the MIT License - see the LICENSE file for details.

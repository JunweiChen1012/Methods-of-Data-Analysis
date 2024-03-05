
# EDA (Exploratory Data Analysis) of Airbnb Listings in Paris

## Overview of Paper
This repository contains an R script and a research paper analyzing n data from Airbnb listings in Paris, fetched directly from the Airbnb website. The dataset includes various features of the listings such as host details, property attributes, and review scores. For inquiries or further information, please contact Junwei Chen at junwei.chen@mail.utoronto.ca.

## File Structure

-   `outputs/paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper.

-   `scripts` contains the R scripts used to simulate, download, clean and validate data, as well as helper functions used in these routines.

## How to Use
Prerequisites: Ensure you have R installed on your system along with the RStudio IDE for an optimal experience.
Installation: Clone this repository and open the project in RStudio.
Dependencies: Install the required R libraries by running:
- R
- Copy co
`install.packages(c("janitor", "knitr", "lubridate", "naniar", "tidyverse"))`
Execution: Open the script EDA_Airbnb_Paris.Rmd and run it in RStudio to perform the analysis. Make sure you have an internet connection as the script fetches the latest data from the Airbnb website.
Libraries Used
Janitor: For cleaning data.
Knitr: For creating dynamic reports.
Lubridate: For handling date and time data.
Naniar: For handling missing values.
Tidyverse: For data manipulation and visualization.


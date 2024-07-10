---
title: "Airbnb France Project"
output: github_document
---

# Airbnb France

## Introduction

This repository contains the code and data for preparing a dataset from Airbnb listings in France and creating an RShiny application to visualize and analyze the data. The project focuses on three major cities: Paris, Lyon, and Bordeaux.

## Contents

- **R Markdown Report**: A comprehensive report detailing the steps taken to prepare the dataset and perform the analysis.
- **R Markdown Report PDF**: A PDF report of project
- **Code**: The codes of the project

## Files

- `Airbnbmarkdown.Rmd`: The R Markdown file containing the full analysis and dataset preparation steps.
- `AirBnb_Rcode.R`: The R code for the project.
- `AirbnbMarkdown.pdf`: The pdf of the project report


## Data Sources

The data used in this project is sourced from [InsideAirbnb.com](http://insideairbnb.com/), a platform that provides detailed information about Airbnb listings in various cities around the world.

## Setup Instructions

To run the code and RShiny app locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/ohnogaurav/Rprogramming.git
    cd Rprogramming
    ```

2. **Install the required R packages**:
    ```r
    install.packages(c("dplyr", "lubridate", "stringr", "ggplot2", "tm", "wordcloud", "shiny"))
    ```

3. **Run the R Markdown file**:
    Open `Airbnbmarkdown.Rmd` in RStudio and knit the document to generate the HTML report.

4. **Run the RShiny app**:
    ```r
    shiny::runApp("app")
    ```

## Acknowledgments

I would like to acknowledge the following sources and individuals for their assistance and contributions to this project:

- **OpenAI's ChatGPT**: For providing guidance and assistance in understanding R, RShiny, and data preparation techniques.
- **Stack Overflow**: For offering valuable solutions to specific coding challenges encountered during the project.
- **InsideAirbnb.com**: For providing the dataset used in the analysis.
- [Airbnb Database Rstudio](https://www.shinyapps.io/admin/#/application/7532802): For serving as an inspiration and reference for the development of the RShiny app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

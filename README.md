# Flight Delay Analysis (2013–2023)

An R-based exploration of U.S. flight delays using Generalized Additive Models (GAMs) and regression. We model normalized delay ratios, achieve up to **97%** prediction accuracy, and uncover seasonal trends and anomalies related to COVID-19.

---

## 📂 Repository Structure

- **`code/`** – R Markdown source (`flight_delay_analysis.Rmd`)  
- **`data/`** – raw dataset (`Airline_Delay_Cause.csv`)  
- **`docs/`** – rendered HTML report (`flight_delay_analysis.html`)  
- **`figures/`** – standalone plot images  

---

## 📖 Usage

1. **Clone** this repo:  
   ```bash
   git clone https://github.com/<your-username>/flight-delay-analysis.git
   cd flight-delay-analysis

2.Install dependencies in R:
install.packages(c(
  "mgcv", "ggplot2", "dplyr", "tidyr", 
  "reshape2", "patchwork", "ggrepel", 
  "summarytools", "knitr", "rmarkdown"
))

3.Render the report:
rmarkdown::render(
  "code/flight_delay_analysis.Rmd",
  output_file = "../docs/flight_delay_analysis.html"
)
4.Open the report in your browser:
docs/flight_delay_analysis.html


Dataset
We use the Flight Delay Data for U.S. Airports by Carrier (August 2013 – August 2023), originally published on Kaggle:
https://www.kaggle.com/datasets/eugeniyosetrov/flights-data?resource=download

Author
Farzaneh Yousefi

# Bathing Water Quality Analysis (Yorkshire Coast)
This project explores the relationship between environmental variables and bathing water quality at a coastal site in Yorkshire, UK. It was developed as part of the MSc Environmental Data Science and Analytics programme at the University of Leeds.

The aim is to identify how wind speed, wave height, and air temperature may influence bacterial contamination levels, with a focus on supporting public health decisions and improving early warning systems. The project simulates the kind of data-led public good research seen in LIDA's collaborations with agencies like the Environment Agency.

## 📊 Key Features
- **Time Series Visualisation**  
  Uses `plotly.graph_objects` and `matplotlib` to plot 15-minute resolution environmental data.

- **Multi-Panel Dashboard Layout**  
  Custom `make_subplots` dashboard of three environmental parameters, allowing easy visual comparison.

- **Exploratory Data Analysis**  
  Identifies potential correlations and trends that could influence bathing water safety.

- **Stakeholder-Orientated Communication**  
  Designed to be accessible to non-technical audiences with clear visuals and narrative explanation.

## 🛠️ Tools and Libraries Used
- Python 3  
- Jupyter Notebook  
- Pandas  
- Plotly  
- Matplotlib  
- Seaborn

## 📁 File Structure
bathing-water-quality/
├── AssessingBathingWaterQuality.ipynb # Main analysis notebook
├── README.md # Project overview and usage instructions

## 🚀 Getting Started
1. Clone or download this repository.
2. Open the `.ipynb` file in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to follow the analysis.

## 🔍 Insights
- Environmental drivers such as wind and wave height may indicate short-term fluctuations in bathing water quality.
- Dashboard-style visualisations help surface patterns that are difficult to detect using summary statistics alone.
- Designed to support early-stage public health monitoring and improve stakeholder decision-making.

## 👤 Author
**Hannah Green**  
MSc Environmental Data Science and Analytics  
University of Leeds

## 📜 Acknowledgements
Project developed as part of university coursework inspired by real-world public good data challenges.  
Environmental datasets sourced from simulated 15-minute resolution inputs for academic purposes.

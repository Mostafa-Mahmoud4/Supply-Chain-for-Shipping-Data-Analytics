# Supply Chain Shipment Pricing Data - Data Analysis and Modeling

This project focuses on the analysis and modeling of a supply chain shipment dataset. The goal is to explore the dataset, visualize key insights, and conduct basic analytics on shipment modes, countries, and manufacturing sites.

## Dataset

The dataset used in this project is the [SCMS Delivery History Dataset](https://raw.githubusercontent.com/rajeevratan84/data-analyst-bootcamp/master/SCMS_Delivery_History_Dataset.csv).

The dataset provides details on various shipments, including information such as shipment mode, pack price, country of shipment, manufacturing site, and other key features.

## Project Highlights

- **Data Preprocessing**: Dropped missing values for cleaner analysis.
- **Exploratory Data Analysis (EDA)**:
  - Top 10 countries by the number of shipments.
  - Shipment modes analyzed using both bar charts and pie charts.
  - Total pack price distribution for the top 15 countries.
  - First Line Designation-wise shipment analysis.
- **Visualizations**: 
  - Bar plots for shipment counts and total pack prices.
  - Pie chart representing shipment mode percentages.
- **Shipment Mode Analysis**: 
  - Analyzed min, max, and mean shipment sizes for the Air shipment mode.
- **Top Manufacturing Sites**: 
  - Identified the top 10 manufacturing sites overall, and for the Air shipment mode specifically.

## Key Results

- **Top Country by Pack Price**: Nigeria (25,620.72)
- **Top Shipment Mode**: Air
- **Air Shipment Statistics**:
  - Max: 1000 units
  - Min: 1 unit
  - Mean: 82.35 units
- **Top Manufacturing Site**: Aurobindo Unit III, India
  - Total Shipments: 3172
  - Air Shipments: 1694

## How to Run

1. Clone the repository.
2. Install required packages:
   
     pip install pandas numpy seaborn matplotlib plotly
   
3. Run the notebook to explore and visualize the dataset.

## Visualizations

The project includes various visualizations like bar charts and pie charts that help uncover the shipment patterns for different countries, shipment modes, and manufacturing sites.

## Conclusion

This analysis provides insights into the shipment modes and pricing patterns across different countries and manufacturing sites. The data reveals key players in the supply chain logistics space and sheds light on how different shipment methods impact shipment size and frequency.

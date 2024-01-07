

# Customer Segmentation using RFM Modeling

## Overview
This project focuses on segmenting customers of a UK-based, online non-store retail company using RFM (Recency, Frequency, Monetary) analysis. The company specializes in unique, all-occasion gifts, and has a broad customer base, including many wholesalers.

## Dataset
The dataset for this project is a transnational dataset containing transactions from 01/12/2010 to 09/12/2011. It offers insights into the buying patterns of the company's customers.

### Data Attributes
- **InvoiceNo**: Invoice number (Nominal)
- **StockCode**: Item code (Nominal)
- **Description**: Item description (Nominal)
- **Quantity**: The quantities of each item per transaction (Numeric)
- **InvoiceDate**: Invoice Date and time (Numeric, can be converted to DateTime)
- **UnitPrice**: Unit price (Numeric)
- **CustomerID**: Customer number (Nominal)
- **Country**: Country name (Nominal)

## Methodology
The RFM modeling approach is used to analyze customer value based on three dimensions:
- **Recency (R)**: How recently a customer has made a purchase
- **Frequency (F)**: How often a customer makes a purchase
- **Monetary (M)**: How much money a customer spends on purchases

## Tools and Technologies
- Python
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Jupyter Notebook

## Findings
- **Customer Segmentation**: The analysis reveals distinct segments of customers based on RFM scores.
- **Behavioral Insights**: The segments display varied behavioral traits which can be leveraged for targeted marketing strategies.

## Usage
1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter Notebook `Customer_Segmentation_using_RFM_Modeling.ipynb`.

## Contributing
Contributions, issues, and feature requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
- This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
- DOI: [10.24432/C5BW33](https://doi.org/10.24432/C5BW33)

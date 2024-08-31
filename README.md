# Supply Chain Input-Output Analysis App

This Streamlit application provides an interactive interface for analyzing the input-output relationships of industries and products in the UK economy. The application consists of multiple pages that allow users to explore how different industries use goods and services in their production processes, the inputs required for producing various products, and the effects of changes in final use on the economy.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Pages](#pages)
- [Data](#data)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Interactive Visualizations:** Use Plotly charts to visualize data.
- **Data Exploration:** Explore raw data in tabular form.
- **User Input:** Select products and view data in different formats (values or percentages).
- **Economic Impact Analysis:** Model the effects of changes in final use on the economy.

## Installation

To run this application, you need to have Python and Streamlit installed. You can install the required packages using pip:

```sh
pip install streamlit pandas plotly
```
## Usage
Clone the repository:
```
git clone https://github.com/your-username/supply-chain-IOA-app.git
cd supply-chain-IOA-app
```
Run the Streamlit application:
```
streamlit run your_script_name.py
```
Replace your_script_name.py with the name of the Python script containing the Streamlit code.

## Pages
1. Industry Use of Products
This page presents information on the extent to which different industries in the economy use specific goods and services in their production processes. Users can select a product and view data in either values (£m) or as proportions of total intermediate consumption needed to produce the product.

2. Inputs into the Production Process
This page examines what products (goods and services) need to be used in order to produce other products, and of these, what proportion are domestically produced and which imported. It utilizes the ONS product-by-product tables, which are part of the Input-Output tables.

3. Effects of a Change in Final Use
This page allows the user to model the total effect of a change in final use on the economy. The effects published by ONS are sometimes referred to as Type 1. They include the impact on production of a change in final use (direct impact) and the supply chain impacts stemming from the initial change in final use (indirect impact).

## Data
The application uses CSV files located in the data directory. The files include:

combined_pi.csv: Data on the input requirements of products.
combined.csv: Data on the inputs into the production process.
detailed_effects.csv: Data on the effects of changes in final use on the economy.
Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

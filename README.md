# EDA on Click-Through Rate (CTR) Advertising Dataset

This project performs an Exploratory Data Analysis (EDA) on a click-through rate (CTR) advertising dataset. The goal is to understand the data, identify patterns, and extract insights that can inform business decisions.

## Project Structure

- `EDA_on_Click-on-Adv.ipynb`: Jupyter notebook containing the EDA.
- `advertising.csv`: Dataset used for the analysis.

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn
```
## Usage
1. Clone the repository:
``` bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```
2. Open the Jupyter notebook:
``` bash
jupyter notebook EDA_on_Click-on-Adv.ipynb
```
3. Run the cells in the notebook to see the analysis.
## Dataset

The `advertising.csv` file contains the following columns:

- **Daily Time Spent on Site**: Consumer time on site in minutes.
- **Age**: Customer age in years.
- **Area Income**: Average income of geographical area of consumer.
- **Daily Internet Usage**: Average minutes a consumer spends on the internet per day.
- **Ad Topic Line**: Headline of the advertisement.
- **City**: City of consumer.
- **Male**: Whether or not the consumer was male.
- **Country**: Country of consumer.
- **Timestamp**: Time at which consumer clicked on Ad or closed window.
- **Clicked on Ad**: 0 or 1 indicated clicking on Ad.

## Analysis

The EDA includes:

- **Data Cleaning**: Handling missing values and correcting data types.
- **Data Visualization**: Plotting distributions, correlations, and trends.
- **Statistical Analysis**: Examining relationships between variables.

## Results

The key insights from the analysis are:

- Relationship between age and click-through rates.
- Impact of daily internet usage on advertisement clicks.
- Influence of area income on consumer behavior.

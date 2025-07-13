# Zomato Restaurant Data Cleaning Pipeline

A streamlined data cleaning pipeline for a Zomato restaurant dataset, preparing it for seamless analysis and visualization in Tableau.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Data Cleaning Steps](#data-cleaning-steps)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Output Files](#output-files)
- [Tableau Visualization Ideas](#tableau-visualization-ideas)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview
This repository contains a Google Colab / Jupyter Notebook workflow (`ZomatoData.ipynb`) to clean a comprehensive dataset of restaurants from Zomato. The cleaned data is ready for downstream visualization and analysis using Tableau or other BI platforms.

---

## Dataset Description
The dataset includes:
- Restaurant details: name, address, location
- Online ordering & table booking availability
- Ratings and vote counts
- Cuisine types and restaurant categories
- Cost estimate for two people

---

## Data Cleaning Steps
All cleaning steps are documented in `ZomatoData.ipynb`:

1. **Remove Duplicates** – Ensure each restaurant entry is unique  
2. **Handle Data Types** – Convert rating and cost to numeric; order/book fields to boolean  
3. **Handle Missing Values** – Use median for numeric and placeholders (`'Unknown'`, `'Various'`) for categories  
4. **Standardize Casing & Renaming** – Title-case key text fields and lowercase all column names for consistency

---

## Getting Started

### Prerequisites
Ensure you have Python 3.7+ installed. Install required packages:

```bash
pip install -r requirements.txt
```

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/adityamehta93/zomato_data_analysis.git
   cd zomato_data_analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
- Open `ZomatoData.ipynb` in **Google Colab** or **Jupyter Notebook**
- Run all cells to:
  1. Load the dataset from Google Drive
  2. Perform cleaning and preprocessing
  3. Export your cleaned dataset for analysis

---

## Output Files

| File                          | Description                                  |
|-------------------------------|----------------------------------------------|
| `ZomatoData.ipynb`            | Notebook with cleaning logic                 |
| `requirements.txt`            | Python package dependencies                  |

---

## Tableau Visualization Ideas

Here are some suggested visualizations you can build in Tableau:

- **Average Rating by Location** – Find top-performing areas  
- **Cost for Two by Cuisine** – Compare affordability across cuisines  
- **Online Ordering vs Rating** – Analyze influence of delivery options  
- **Restaurant Type Distribution** – Visualize frequency of types  
- **Null Distribution (Before/After Cleaning)** – For documentation  

---

## License

This project is licensed under the **MIT License**. See `LICENSE` file for details.

---

## Contact

Made by Aditya Mehta  
- GitHub: [adityamehta93](https://github.com/adityamehta93/)
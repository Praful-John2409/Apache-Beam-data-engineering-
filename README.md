# Apache Beam and Data Engineering Projects

Welcome to the **Apache Beam and Data Engineering Projects** repository! This repository showcases a series of assignments focused on exploring advanced EDA (Exploratory Data Analysis) techniques, automating EDA with popular Python tools, and demonstrating key features of Apache Beam in a comprehensive manner. The primary goal of this project collection is to push the boundaries of data visualization and data engineering using cutting-edge libraries and frameworks.

---

## Repository Structure

The repository is structured to clearly separate different tasks and their related artifacts. Below is an overview:

```
├── AutoEDA using Sweetviz
│   ├── black_friday
│   │   ├── test.csv
│   │   └── train.csv
│   ├── Sweetviz_colab.ipynb
│   └── Sweetviz_Comparative_Report.html
│
├── EDA using D3JS
│   ├── EDA dataset
│   │   └── movies_metadata.csv
│   ├── EDA_on_movies_metadata_using_D3js_colab.ipynb
│   └── README.md
│
├── Apache_beam_features.ipynb
├── README.md
```

---
## Introduction

This repository comprises three primary tasks, each focusing on different aspects of data engineering and analysis. The tasks include:

1. **Advanced Exploratory Data Analysis (EDA) with D3.js**: Using the *movies_metadata.csv* dataset from Kaggle, this task demonstrates the power of D3.js visualizations to uncover insights from data in an interactive manner.
2. **Automated EDA with Sweetviz**: This task automates the EDA process using Sweetviz, showcasing how we can quickly gain an understanding of the data's structure and relationships, using the *Black Friday* dataset.
3. **Apache Beam Features**: A hands-on demonstration of various Apache Beam features, including composite transforms, pipeline I/O, triggers, windowing, ParDo, and streaming, all implemented in a Google Colab notebook.
- **Colab Link**: Access all Colab notebooks from the shared Google Drive link [here](https://drive.google.com/drive/folders/1aLWV_Fa05_qkf67GlVBfvSiaQOpPD8EE?usp=sharing).
## Detailed Task Descriptions

### 1. Advanced EDA Using D3.js
**Colab Notebook**: [EDA on Movies Metadata using D3.js](https://drive.google.com/drive/folders/1aLWV_Fa05_qkf67GlVBfvSiaQOpPD8EE?usp=sharing)

- **Dataset**: The *movies_metadata.csv* dataset contains detailed metadata of movies, such as titles, genres, budget, revenue, release dates, and more, with 45,466 entries and 24 columns. We analyze various features, like budget and revenue, to extract meaningful patterns and relationships.
- **Description**: This task demonstrates how to perform a thorough EDA using advanced D3.js visualizations. By leveraging D3.js, we bring the data to life, creating interactive and visually appealing charts that reveal the nuances in the dataset. Examples include genre distributions, correlations between budget and revenue, and popularity trends over time.
- **Artifacts**:
  - `movies_metadata.csv`: The primary dataset used for analysis.
  - `EDA_on_movies_metadata_using_D3js_colab.ipynb`: The Colab notebook where all D3.js visualizations and analyses are implemented.

### 2. Automated EDA Using Sweetviz
**Colab Notebook**: [Sweetviz Colab](https://drive.google.com/drive/folders/1aLWV_Fa05_qkf67GlVBfvSiaQOpPD8EE?usp=sharing)

- **Dataset**: The *Black Friday* dataset, which includes information about customer purchases, such as User_ID, Product_ID, Gender, Age, Occupation, City_Category, Marital_Status, and Product Categories. It has 550,068 entries in the training set.
- **Description**: This task utilizes Sweetviz, a Python library for automated EDA, to create an easy-to-understand comparative report. Sweetviz generates interactive HTML reports that offer a comprehensive overview of the data, highlighting key insights such as data distributions, correlations, and missing values.
- **Artifacts**:
  - `train.csv` & `test.csv`: The training and testing datasets used in the analysis.
  - `Sweetviz_colab.ipynb`: The Colab notebook demonstrating the automated EDA process.
  - `Sweetviz_Comparative_Report.html`: An HTML report generated by Sweetviz, summarizing the entire dataset.

### 3. Apache Beam Features
**Colab Notebook**: [Apache Beam Features Colab](https://drive.google.com/drive/folders/1aLWV_Fa05_qkf67GlVBfvSiaQOpPD8EE?usp=sharing)

- **Description**: This task focuses on implementing and demonstrating core Apache Beam features in a Google Colab environment. We explore concepts such as:
  - **Composite Transforms**: Combining multiple transforms into a single logical unit.
  - **Pipeline I/O**: Reading and writing data in various formats.
  - **Triggers and Windowing**: Controlling how data is aggregated and when results are emitted.
  - **ParDo**: Performing element-wise operations on a PCollection.
  - **Streaming**: Handling real-time data processing.
- **Artifacts**:
  - `Apache_beam_features.ipynb`: The Colab notebook that explains and demonstrates these Apache Beam features with relevant code and explanations.

## How to Use This Repository

1. **Clone the Repository**: Use the following command to clone this repository to your local machine:
   ```bash
   git clone https://github.com/Praful-John2409/Apache-Beam-data-engineering-.git
   ```
2. **Open Colab Notebooks**: Use Google Colab to open and run the provided notebooks. Follow the instructions below for each task:
   - **For D3.js Visualizations**: Open the `EDA_on_movies_metadata_using_D3js_colab.ipynb` and upload the `movies_metadata.csv` dataset when prompted.
   - **For Sweetviz Analysis**: Open the `Sweetviz_colab.ipynb` and upload `train.csv` and `test.csv` datasets.
   - **For Apache Beam Features**: Open `Apache_beam_features.ipynb` and run the code cells to explore various Apache Beam concepts.

3. **Data Upload**: Ensure that you upload the datasets (if required) when prompted in Google Colab. This step is crucial for the notebooks to function correctly.

## Additional Notes

- **Requirements**: Make sure to have Python 3 and all necessary libraries installed if running the notebooks locally. Google Colab will handle most dependencies automatically.
- **Interactive Reports**: The Sweetviz-generated HTML report can be opened in any web browser to view the EDA results.


## Conclusion

This repository provides a comprehensive exploration of data analysis and data engineering techniques. 

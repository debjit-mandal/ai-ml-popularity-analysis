
# AI and ML Popularity Analysis

This project provides a comprehensive analysis of the global popularity trends of Artificial Intelligence (AI) and Machine Learning (ML). The data includes information gathered from various sources such as search engine queries, social media mentions, research publications, online course enrollments, and job postings.

## Table of Contents

- [AI and ML Popularity Analysis](#ai-and-ml-popularity-analysis)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset](#dataset)
  - [Project Structure](#project-structure)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Analysis](#analysis)
    - [Data Preprocessing](#data-preprocessing)
    - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
    - [Clustering Analysis](#clustering-analysis)
    - [Time Series Analysis](#time-series-analysis)
    - [Statistical Analysis](#statistical-analysis)
  - [Insights and Conclusion](#insights-and-conclusion)
  - [Contributing](#contributing)
  - [License](#license)

## Overview

This project aims to analyze the popularity trends of AI and ML using a dataset that aggregates information from multiple sources. The analysis includes data preprocessing, exploratory data analysis, principal component analysis, clustering analysis, time series analysis, and statistical analysis to derive insights and conclusions.

## Dataset

The dataset used in this project includes the following information:
- Search engine query data
- Social media mentions and hashtags
- Research publication counts
- Online course enrollments
- Job postings

## Project Structure

```
ai-ml-popularity-analysis/
├── data/
│   └── Ai and Ml popularity.csv
├── notebooks/
│   └── ai_ml_popularity_analysis.ipynb
├── README.md
└── LICENSE
```

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/debjit-mandal/ai-ml-popularity-analysis.git
   ```

2. Navigate to the project directory:

   ```sh
   cd ai-ml-popularity-analysis
   ```

3. Create and activate a virtual environment (optional but recommended):

   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

4. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:

   ```sh
   jupyter notebook notebooks/ai_ml_popularity_analysis.ipynb
   ```

2. Follow the instructions in the notebook to explore the analysis.

## Analysis

### Data Preprocessing

- Handle missing values by filling them with the mean of the respective columns.
- Standardize numerical columns for better comparison.

### Exploratory Data Analysis (EDA)

- Visualize relationships between features using pairplots.
- Generate a correlation matrix to understand correlations between different variables.

### Principal Component Analysis (PCA)

- Reduce the dimensionality of the dataset and identify the principal components that explain the most variance in the data.
- Visualize the PCA results.

### Clustering Analysis

- Perform K-Means clustering to identify different clusters in the dataset based on the popularity metrics.
- Visualize the clusters using PCA components.

### Time Series Analysis

- Analyze trends over time to understand how the popularity of AI and ML has evolved.
- Create a dummy 'Year' column for demonstration and plot the trends.

### Statistical Analysis

- Calculate Pearson correlation between key features.
- Perform a t-test to compare the popularity between two groups (e.g., China and Vietnam).

## Insights and Conclusion

- **PCA Analysis**: The principal component analysis helped reduce the dimensionality of the dataset and visualize the variance explained by the principal components.
- **Clustering Analysis**: K-Means clustering identified three distinct clusters in the dataset, representing different groups of countries or cities with similar popularity trends in AI and ML.
- **Time Series Analysis**: The time series analysis showed an increasing trend in the popularity of AI and ML over the years, indicating a growing interest and adoption of these technologies.
- **Statistical Analysis**: The Pearson correlation analysis revealed a strong positive correlation between different popularity metrics. The t-test showed a significant difference in the popularity of AI and ML between China and Vietnam.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

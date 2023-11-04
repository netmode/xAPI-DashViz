# xAPI Learning Analytics Dashboard

## Overview

This dashboard provides visual analytics and insights into learning activities captured through the xAPI (Experience API). It enables educators and learners to track engagement metrics, assess learning outcomes, and identify patterns in learning behavior.

## Features

- **Learner Interaction Overview:** Visualizes the total number of interactions per learner, allowing for quick identification of the most and least active learners.
- **Verb Frequency Analysis:** Breaks down the frequency of xAPI verbs used in the learning activities, offering insights into the types of interactions.
- **Time Spent Analysis:** Calculates and displays the total time learners spend on learning materials, highlighting engagement levels.
- **Material Diversity Inspection:** Examines the range of materials each learner interacts with, indicating the breadth of resource utilization.
- **Clustering Techniques Comparison:** Applies DBSCAN, K-means, and Hierarchical Clustering to segment learners based on activity count, time spent, and unique materials count.
- **SHAP Value Explanation:** Utilizes SHAP values to explain the clustering model, giving an interpretative view of the feature influences on the learner groupings.

## Prerequisites

To run this dashboard, you will need the following libraries installed:

- `dash`
- `dash_core_components`
- `dash_html_components`
- `dash_bootstrap_components`
- `plotly`
- `pandas`
- `numpy`
- `scikit-learn`
- `xgboost`
- `shap`
- `lifelines` (optional for survival analysis)
- `pm4py` (optional for process mining)

## Usage
Once the Jupyter Notebook is running:

- Navigate through the cells and run them sequentially to launch the Dash application.
- Access the dashboard through the provided web URL, typically http://127.0.0.1:8050/ in your web browser.
- Interact with the dashboard's various features to gain insights into the xAPI learning data.

## Installation

1. Clone the repository or download the Jupyter Notebook.
2. Ensure that you have Python installed on your system.
3. Install the necessary libraries by running:

```bash
pip install dash dash-core-components dash-html-components dash-bootstrap-components plotly pandas numpy scikit-learn xgboost shap lifelines pm4py

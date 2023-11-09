# xAPI Data Fetching and Processing Script

## Overview

This Python script is designed to fetch xAPI data from a specified Trax Learning Record Store (LRS) using basic authentication and a designated API key from Trax. It includes functions for data retrieval, cleaning, and transformation into a tabular format. The resulting data is stored in a Pandas DataFrame for further analysis.

## Prerequisites

Before using this script, ensure you have basic HTTP username and password authentication, an API Key provided by TraxLRS, and the necessary dependencies installed. You can install them using:

```bash
pip install requests numpy pandas

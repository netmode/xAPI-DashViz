# xAPI Data Fetching and Processing Script

## Overview

This Python script is designed to fetch xAPI data from a specified Trax Learning Record Store (LRS) using basic authentication and a designated API key from Trax. It includes functions for data retrieval, cleaning, and transformation into a tabular format. The resulting data is stored in a Pandas DataFrame for further analysis.

## Prerequisites

Before using this script, ensure you have basic HTTP username and password authentication, an API Key provided by TraxLRS, and the necessary dependencies installed. You can install them using:

```bash
pip install requests numpy pandas
```

## Usage

### 1. Authentication and API Key

Replace the placeholder values in the script with your actual LRS credentials:

```python
user = 'your_username'
password = 'your_password'
api_key = 'your_api_key'
```

## 2. Time Period Parameters

Adjust the `prev` and `curr` parameters to specify the time period for data extraction:

```python
prev = 'yyyy-mm-ddTHH:MM:SSZ'  # Start date and time
curr = 'yyyy-mm-ddTHH:MM:SSZ'  # End date and time
```

## 3. Data Extraction Limit

Set the desired limit for the number of statements to retrieve:

```python
limit = 10
```

## 4. Execute the Script

Run the script, and the cleaned and formatted data will be stored in a Pandas DataFrame named `df`:

```bash
python your_script_name.py
```

## Contributing

Feel free to contribute to the development of this script by submitting issues or pull requests.

## License

This script is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


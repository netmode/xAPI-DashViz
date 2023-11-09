<!DOCTYPE html>
<html>

<head>
    <title>xAPI Data Fetching and Processing Script</title>
</head>

<body>

    <h1>xAPI Data Fetching and Processing Script</h1>

    <h2>Description</h2>
    <p>This Python script is designed to fetch xAPI data from a specified Trax Learning Record Store (LRS) using basic authentication and a designated API key from Trax. It includes functions for data retrieval, cleaning, and transformation into a tabular format. The resulting data is stored in a Pandas DataFrame for further analysis.</p>

    <h2>Prerequisites</h2>
    <p>Before using this script, ensure you have basic http username and password authentication, an API Key provided by TraxLRS, and the necessary dependencies installed. You can install them using:</p>
    <code>pip install requests numpy pandas</code>

    <h2>Usage</h2>

    <h3>1. Authentication and API Key</h3>
    <p>Replace the placeholder values in the script with your actual LRS credentials:</p>
    <pre>
user = 'your_username'
password = 'your_password'
api_key = 'your_api_key'
    </pre>

    <h3>2. Time Period Parameters</h3>
    <p>Adjust the <code>prev</code> and <code>curr</code> parameters to specify the time period for data extraction:</p>
    <pre>
prev = 'yyyy-mm-ddTHH:MM:SSZ'  # Start date and time
curr = 'yyyy-mm-ddTHH:MM:SSZ'  # End date and time
    </pre>

    <h3>3. Data Extraction Limit</h3>
    <p>Set the desired limit for the number of statements to retrieve:</p>
    <pre>
limit = 10
    </pre>

    <h3>4. Execute the Script</h3>
    <p>Run the script, and the cleaned and formatted data will be stored in a Pandas DataFrame named <code>df</code>:</p>
    <code>python your_script_name.py</code>

    <!-- Include additional sections for other functions if needed -->

    <h2>Contributing</h2>
    <p>Feel free to contribute to the development of this script by submitting issues or pull requests.</p>

    <h2>License</h2>
    <p>This script is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

</body>

</html>

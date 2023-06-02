# Phishing Website Detection

This code is a Python script for detecting phishing websites using various machine learning models. It reads a dataset of website features and performs data analysis, visualization, and classification using different classification algorithms.

## Table of Contents
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Data Analysis](#data-analysis)
- [Data Visualization](#data-visualization)
- [Contributing](#contributing)


## Dependencies
- `os`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `missingno`
- `sklearn`
- `xgboost`

Install the required dependencies using the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Download the dataset file (`dataset.csv`) and place it in the same directory as the script.
2. Run the script using a Python interpreter.
3. The script will perform the following steps:
   - Read the dataset file.
   - Perform data analysis and visualization.
   - Split the data into training and testing sets.
   - Initialize and train multiple classification models.
   - Evaluate the performance of each model using accuracy, classification report, and confusion matrix.
4. The results will be displayed in the console and visualized using matplotlib and seaborn.

Note: Ensure that you have the necessary permissions to read the dataset file and install the required dependencies.

## Dataset
The dataset file (`dataset.csv`) contains the following columns:
- `having_IPhaving_IP_Address`
- `URLURL_Length`
- `Shortining_Service`
- `having_At_Symbol`
- `double_slash_redirecting`
- `Prefix_Suffix`
- `having_Sub_Domain`
- `SSLfinal_State`
- `Domain_registeration_length`
- `Favicon`
- `port`
- `HTTPS_token`
- `Request_URL`
- `URL_of_Anchor`
- `Links_in_tags`
- `SFH`
- `Submitting_to_email`
- `Abnormal_URL`
- `Redirect`
- `on_mouseover`
- `RightClick`
- `popUpWidnow`
- `Iframe`
- `age_of_domain`
- `DNSRecord`
- `web_traffic`
- `Page_Rank`
- `Google_Index`
- `Links_pointing_to_page`
- `Statistical_report`
- `Result`

## Data Analysis

Include a description of the data analysis performed, such as reading the dataset, checking for missing values, dropping duplicates, and exploring the data.

## Data Visualization

Include a description of the data visualization performed, such as plotting histograms, heatmaps, scatter plots, etc.

## Contributing

Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

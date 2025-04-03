# data1202_project
## Short Description
This project analyzes a dataset containing YouTube channel data and calculates the distribution of different channel types among the top 1000 entries. The results are saved to a CSV file for further analysis. 

## Getting Started
### Prerequisites
1. Python (Version 3.6 or higher)
2. Required Python Libraries:
   - Pandas
   - Numpy
   - MySQL Connector (for future analysis)

### Installing
1. Clone the repository or download the script file.
2. Install required dependencies.
   You can install the required libraries using the following command:
      ```sh
      pip install pandas numpy mysql-connector-python
      ```
4. Ensure `youtube_dataset.csv` is in the working directory.

## Running the Tests
### Breakdown of Tests
This script performs:
- Data loading: Reads a CSV file containing YouTube channel data.
- Data cleaning: Removes rows with missing values (NaNs)in the channeltype column.
- Distribution calculation: Calculates the distribution of channel types from the top 1000 rows.
- Result saved: Saves the calculated distribution to a CSV file named channel_distribution.csv.
- CSV output validation: S

## Deployment
This script is intended for local execution but can be expanded to run in cloud environments.

## Author
Ushna Laraib

## License
This project is licensed under the MIT License.

## Acknowledgement
- Data sourced from YouTube dataset.
- Pandas library for data processing.
"""

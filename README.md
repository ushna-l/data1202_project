# data1202_project
## Short Description
This project analyzes a dataset containing YouTube channel data and calculates the distribution of different channel types among the top 1000 entries.

## Getting Started
### Prerequisites
- Python 3.x
- Pandas
- MySQL Connector (if needed for future expansion)

### Installing
1. Clone the repository.
2. Install required dependencies:
   ```sh
   pip install pandas mysql-connector-python
   ```
3. Ensure `youtube_dataset.csv` is in the working directory.

## Running the Tests
### Breakdown of Tests
This script performs:
- Data loading
- Data cleaning (removing NaNs in 'channeltype')
- Distribution calculation
- CSV output validation

## Deployment
This script is intended for local execution but can be expanded to run in cloud environments.

## Author
- Your Name

## License
This project is licensed under the MIT License.

## Acknowledgement
- Data sourced from YouTube dataset.
- Pandas library for data processing.
"""

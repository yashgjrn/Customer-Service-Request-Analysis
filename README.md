# Service Request Analysis

## Overview
This project explores and analyzes municipal service request data to uncover patterns in public nuisance reports and agency response efficiency. By processing large-scale complaint datasets with Python, this project visualizes primary complaint types, geographical distribution across boroughs, and average resolution times.

## Key Insights
* **Vehicular & Parking Issues:** "Blocked Driveway" and "Illegal Parking" constitute the vast majority of service requests, indicating severe logistical bottlenecks.
* **Noise Pollution:** Street/sidewalk and commercial noise rank as the second most prevalent issue, primarily driven by "Loud Music/Party" descriptors.
* **Location Hotspots:** The overwhelming majority of incidents occur in public transit arteries (streets and sidewalks) rather than residential buildings.
* **Resolution Efficiency:** Tracks agency performance, highlighting an average median resolution time of roughly 2 hours and 42 minutes for standard complaints.

## Technologies Used
* **Python** 
* **Pandas** (Data manipulation, aggregation, and time-delta calculations)
* **Matplotlib** (Data visualization and charting)

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/Service-Request-Analysis.git](https://github.com/YourUsername/Service-Request-Analysis.git)
   cd Service-Request-Analysis
   ```

2. **Install the required dependencies:**
   Make sure you have Python installed, then install the necessary libraries:
   ```bash
   pip install pandas matplotlib
   ```

3. **Add the dataset:**
   Place your dataset (e.g., `311_Service_Requests.csv`) into the root directory of the project.

## Usage
Run the main Python script from your terminal to clean the data and generate the visualization charts:
   ```bash
   python main.py
   ```
*(Note: If you are working out of a Jupyter Notebook in VS Code, simply open the `.ipynb` file and execute the cells sequentially.)*

## Project Structure
   ```text
   Service-Request-Analysis/
   │
   ├── main.py                # Main script for data processing and visualization
   ├── README.md              # Project documentation
   ├── .gitignore             # Ignored files (e.g., large datasets, __pycache__)
   └── requirements.txt       # (Optional) List of project dependencies
   ```

## Author
* **Yash**

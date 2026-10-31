# Smart City Traffic Flow Simulator

## About the Project

The Smart City Traffic Flow Simulator is a NumPy-based project developed in Google Colab. It simulates hourly vehicle counts for 10 city junctions over 30 days, considering morning and evening rush-hour traffic patterns.

The project analyzes traffic flow, identifies peak congestion hours, and finds potential traffic bottlenecks using NumPy operations.

## Project Objectives

- Simulate traffic data for 30 days.
- Generate hourly vehicle counts for 10 junctions.
- Model morning and evening rush-hour patterns.
- Identify peak traffic hours and potential bottlenecks.
- Compare loop-based and vectorized computations.

## Technologies Used

- Python
- NumPy
- Google Colab


**Note:** NumPy is the only external Python library used in this project.

## Project Specifications

| Parameter | Value |
|---|---:|
| Simulation Duration | 30 Days |
| Number of Junctions | 10 |
| Hours per Day | 24 |
| Total Records | 7,200 |
| Data Generation Method | NumPy Poisson Distribution |

## Key Features

### 1. Traffic Data Simulation
Generates hourly vehicle counts using `np.random.poisson()` with a fixed random seed for reproducibility.

### 2. Rush-Hour Simulation
Models increased traffic during morning and evening peak hours.

### 3. Traffic Aggregation
Uses NumPy operations such as `sum()`, `mean()`, and `argmax()` to analyze traffic across days, junctions, and hours.

### 4. Peak Hour Detection
Identifies the hours with the highest traffic volume and highlights potential bottlenecks.

### 5. Traffic Heatmap
Displays traffic intensity using a NumPy-based text heatmap.

### 6. Performance Comparison
Compares loop-based and vectorized computations using `%timeit` in Google Colab.

## How to Run the Project

1. Download the `.ipynb` notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook**.
4. Upload `Smart_City_Traffic_Flow_Simulator_Numpy_Only.ipynb`.
5. Select **Runtime → Run all**.
6. View the generated traffic analysis and performance comparison.

## Expected Outcomes

- A simulated dataset containing 7,200 junction-hour records.
- Identification of high-traffic hours.
- Comparison of traffic volumes across junctions.
- Detection of potential congestion hotspots.
- Performance comparison between loop-based and vectorized NumPy operations.

## Important Note

This project uses simulated traffic data for educational and analytical purposes. It does not represent actual traffic measurements from a real city.

## Author

Sakshi Rani

## Project Type

NumPy | Data Analysis | Google Colab | Smart City Simulation

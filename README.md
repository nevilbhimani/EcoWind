
# EcoWind: Smart Energy Forecasting and Optimization for Wind Farms

## Overview
EcoWind is a smart energy forecasting and optimization system designed for wind farms. This project leverages machine learning algorithms to predict optimal turbine yaw angles and dynamically adjust turbine settings to maximize power output. The project was developed by Nevil Bhimani, Sarth Patel, and Rohan Rambhiya.

## Features
- Increased wind farm power output by an average of 7.4%
- Achieved 95% prediction accuracy using a robust machine learning framework
- Improved power output by up to 13% under specific wind conditions
- Utilizes SCADA system data for real-time adjustments
- Implements dynamic yaw angle adjustments

## Technologies Used
- Python
- PyTorch
- Amazon SageMaker
- SCADA Systems

## How to Run

### Prerequisites
- Python 3.x
- PyTorch
- Amazon SageMaker SDK
- SCADA System data access

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/final-project.git
   cd final-project
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. **Prepare your SCADA data**:
   - Ensure you have access to the real-time SCADA system data.

2. **Set up the Flask web interface**:
   - Navigate to the project directory and start the Flask server:
     ```bash
     python app.py
     ```

3. **Run the optimization script**:
   - Execute the `final.py` script to start the machine learning-based optimization:
     ```bash
     python final.py
     ```

### Project Structure
- `final.py`: Main script for energy forecasting and optimization.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project documentation.

## Contributors
- Nevil Bhimani
- Sarth Patel
- Rohan Rambhiya

## Acknowledgements
We would like to thank our mentors and the wind farm operators for their support and guidance throughout this project.

 

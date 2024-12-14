# Compost-Dataset

This repository contains the dataset for the research titled:
**"Compost Maturity Prediction and Gas Emissions Monitoring: A Sensor-Based and Interpretable Machine Learning Approach"**.

## Dataset Description
The dataset includes 452 samples collected during the composting process using a dedicated sensor system. It contains key environmental features and gas emission data, enabling predictive analysis for compost maturity and monitoring of gas emissions.

### Features:
- **Day:** Time since the start of the composting process.
- **Temperature:** Temperature readings (in °C).
- **MC (%):** Moisture content percentage.
- **pH:** Acidity or alkalinity of the compost.
- **C/N Ratio:** Carbon-to-nitrogen ratio.
- **Ammonia (mg/kg):** Ammonia concentration in the compost.
- **Nitrate (mg/kg):** Nitrate concentration in the compost.
- **TN (%):** Total nitrogen content.
- **TOC (%):** Total organic carbon content.
- **EC (ms/cm):** Electrical conductivity.
- **OM (%):** Organic matter percentage.
- **T Value:** Transformation value.
- **GI (%):** Germination index percentage.
- **Score:** Compost maturity score.

### Data Collection:
The dataset was collected using a sensor system integrated with Arduino Mega 2560 R3 and ESP-32 microcontrollers. The system wirelessly transmitted data for remote monitoring. Ten datasets were merged after rigorous preprocessing to form this comprehensive dataset. Environmental features such as temperature, C/N ratio, ammonia concentration, pH levels, and nitrate content were analyzed for maturity prediction.

## Usage
Researchers can use this dataset for:
- Developing predictive models for compost maturity.
- Monitoring gas emissions during composting.
- Implementing interpretable machine learning frameworks for environmental data.

### Suggested Tools:
- Python: For data preprocessing, analysis, and model development.
- Machine Learning Libraries: Scikit-learn, XGBoost, CatBoost, LIME, SHAP.

## How to Access the Dataset
The dataset is attached in this repository. You can download it directly using the **"Download"** button or clone the repository:
```bash
git clone https://github.com/hafsa-kibria/Compost-Dataset/blob/main/Compost%20Data.csv 
```

## Citation
If you use this dataset in your research, please cite our work as follows:



## License
This dataset is shared under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to use, modify, and distribute this dataset, provided appropriate credit is given.

## Contact
For any questions or feedback, please contact:
- **Amith Khandakar**: amitk@qu.edu.qa
- **Hafsa Binte Kibria**: hafsabintekibria@gmail.com

---

Thank you for using the Compost-Dataset for your research!

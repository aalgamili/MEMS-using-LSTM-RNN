# MEMS-using-LSTM-RNN
About The code and dataset used in the published paper: Predictive Design of MEMS Gas Sensors Using Bayesian Optimized LSTM Recurrent Neural Networks
# MEMS Gas Sensor Predictive Design using Bayesian Optimized LSTM

This repository contains the code and datasets for the **predictive design of MEMS gas sensors** using **Bayesian-optimized Long Short-Term Memory (LSTM)** networks. The approach integrates **Bayesian optimization** with **LSTM networks** to accurately predict key sensor design parameters (SDPs) such as **resonance frequency**, **quality factor**, and **mass sensitivity** directly from physical structural inputs. This method significantly reduces the reliance on traditional simulation-heavy workflows and accelerates the MEMS sensor design process.

## Key Features
- **Predictive MEMS sensor design** using Bayesian-optimized LSTM models.
- High accuracy in estimating **sensor design parameters (SDPs)**: resonance frequency (fr), quality factor (Q), and mass sensitivity (S).
- Utilizes **Bayesian optimization** for tuning LSTM hyperparameters to enhance convergence and prediction accuracy.
- Demonstrates **simulation-free design** for MEMS sensors based on physical design features.
- **Error metrics**: Achieved **RMSE** and **MAE** values below 2%, indicating high accuracy.
  
## Datasets
### Files
<ol>
  <li><b>sensor_data.csv</b>: The original dataset used for training the Bayesian-optimized LSTM model. Includes sensor parameters such as spring constant, mass, and damping coefficient.</li>
  <li><b>augmented_data.csv</b>: Augmented dataset that includes additional simulated data for better model generalization.</li>
  <li><b>LSTM_Model.py</b>: Python script containing the implementation of the **Bayesian-optimized LSTM** architecture for MEMS sensor prediction.</li>
  <li><b>data_preprocessing.ipynb</b>: Jupyter notebook for preprocessing the sensor dataset, including outlier removal, smoothing, and normalization techniques.</li>
  <li><b>hyperparameter_tuning.ipynb</b>: Jupyter notebook demonstrating how **Bayesian optimization** is applied for hyperparameter tuning of the LSTM model.</li>
  <li><b>training_and_evaluation.ipynb</b>: Jupyter notebook for training the LSTM model, evaluating the model's performance using metrics like RMSE, MAE, and error distributions.</li>
  <li><b>comparison_models.ipynb</b>: Code for comparing the performance of the proposed Bayesian-optimized LSTM model against traditional **CNN**, **GRU**, **Vanilla LSTM**, and **PSO-LSTM** frameworks.</li>
  <li><b>results_figures.ipynb</b>: Jupyter notebook for generating figures like **error distributions**, **prediction vs actual plots**, and **comparison plots** to visualize model performance.</li>
</ol>

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/MEMS_Gas_Sensor_Predictive_Design.git

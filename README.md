# Uncertainty Propagation from Sensor Data to Deep Learning Models in Autonomous Driving
## Overview

Deep learning has been widely used in Autonomous Driving Systems (ADS). Though significant progress has been made regarding their efficiency and accuracy, uncertainty remains a critical factor affecting ADS safety. We focus on the local path planning task in highway driving scenarios. We use Gaussian
Processes to quantify the corresponding Aleatoric Uncertainty (AU). For Epistemic Uncertainty (EU), we employ two classic quantification methods, MC Dropout and Deep Ensembles. More importantly, we also studied the cost-effectiveness of MC Dropout and Deep Ensembles in selecting highly-uncertain samples for facilitating model retraining to improve prediction accuracy.

## Dependencies
* First step is to install the dependencies using requirements.txt file

  ```python
  pip install -r requirements.txt
  ```

## Data
1. We provide two test sets used in our experiments in [Data](https://github.com/ADS-Uncertainty/ADS-Deep-Learning/tree/main/Data), including:
  * Testset
  * Car-following testset

## Usage
1. Download all the files to the local machine.
2. Run the programs in [Data Production](https://github.com/ADS-Uncertainty/ADS-Deep-Learning/tree/main/Program/Data%20Production) sequentially to generate the necessary data files.



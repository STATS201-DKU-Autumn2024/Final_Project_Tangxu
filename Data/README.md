# Predictive Maintenance Data for Vehicle Systems

This project focuses on the **Turbofan Engine Degradation Simulation Data Set** (Saxena and Goebel 2008) from NASA’s Prognostics Data Repository. The dataset consists of time-series sensor data simulating turbofan engines operating under various conditions until failure. It is designed to support predictive maintenance modeling by capturing real-time degradation patterns in high-stress components.

The dataset allows researchers to develop models for early detection of engine faults, contributing to safer and more efficient maintenance strategies in aerospace applications. Each engine in the dataset experiences different levels of initial wear, operational conditions, and fault development, creating a robust testing environment for predictive maintenance algorithms.

## Data Dictionary for the NASA Turbofan Engine Degradation Simulation Dataset (FD001, FD002, FD003, FD004)

| **Variable**           | **Description**                                                                                             | **Type**   | **Unit**          |
|------------------------|-------------------------------------------------------------------------------------------------------------|------------|--------------------|
| UNIT_NUMBER            | Unique identifier for each engine in the dataset.                                                           | Integer    | -                 |
| TIME_CYCLES            | Time in operational cycles, representing a single unit of operation for the engine.                         | Integer    | Cycles            |
| OP_SETTING_1           | Operational setting 1, one of three settings affecting engine performance.                                  | Float      | -                 |
| OP_SETTING_2           | Operational setting 2, affecting engine performance in various conditions.                                  | Float      | -                 |
| OP_SETTING_3           | Operational setting 3, another parameter influencing engine performance under different conditions.         | Float      | -                 |
| SENSOR_1               | Sensor measurement 1, indicative of engine condition and performance.                                       | Float      | -                 |
| SENSOR_2               | Sensor measurement 2, representing real-time engine metrics.                                                | Float      | -                 |
| SENSOR_3 to SENSOR_26  | Additional sensor measurements (3-26) capturing various engine conditions and degradation metrics.          | Float      | -                 |
| RUL (Test Set only)    | Remaining Useful Life (RUL) values provided for test data, indicating the number of cycles remaining until failure. | Integer | Cycles            |

### Dataset Summary
- **FD001**: 100 train and 100 test trajectories, one operational condition (Sea Level) and one fault mode (HPC Degradation).
- **FD002**: 260 train and 259 test trajectories, six operational conditions and one fault mode (HPC Degradation).
- **FD003**: 100 train and 100 test trajectories, one operational condition (Sea Level) and two fault modes (HPC Degradation, Fan Degradation).
- **FD004**: 248 train and 249 test trajectories, six operational conditions and two fault modes (HPC Degradation, Fan Degradation).

## Description of the Dataset
The dataset comprises multiple multivariate time series divided into training and test subsets. Each time series represents the operation of a different engine within a simulated fleet, starting with varying degrees of initial wear and manufacturing variation. Engines operate normally at the beginning of each series and develop faults over time until failure.

The training set includes full degradation cycles until failure, while the test set ends before failure, with the Remaining Useful Life (RUL) values provided for evaluation. The dataset includes three operational settings affecting engine performance and 26 sensor measurements capturing operational metrics. 

This structured dataset is ideal for developing and validating predictive maintenance models for early fault detection and maintenance planning.

## References
- Saxena, A., & Goebel, K. 2008. "Turbofan Engine Degradation Simulation Data Set." NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA. https://data.nasa.gov/Aeorspace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6.

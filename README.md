# CFD-Generated Indoor Climate Dataset

This repository contains computational fluid dynamics (CFD) simulation data for three characteristic positions within an air-conditioned room. The dataset is intended to support research on predictive modeling, environmental intelligence, and HVAC system optimization.

## Dataset Description

Each file corresponds to one sensor location in the simulated domain:

- `Position_1.csv`
- `Position_2.csv`
- `Position_3.csv`

### File Structure

Each CSV file contains four columns:

1. **Time [s]** — simulation time in seconds  
2. **Temperature [°C]** — local air temperature  
3. **Relative Humidity [%]** — local relative humidity  
4. **Air Velocity [m/s]** — local air velocity magnitude  

### Notes

- Data are generated from CFD simulations and do not include sensor noise.  
- The time step and duration reflect the simulation configuration described in the associated manuscript.  
- Units are consistent across all files.  

## Usage

The dataset can be used for:
- Training and evaluating machine learning models (e.g., ANN, LSTM)  
- Studying short-horizon forecasting of indoor climate variables  
- Benchmarking algorithms for adaptive HVAC control and diagnostics  

## Reference

If you use this dataset, please cite the associated paper:

> [Authors], *"Title"*, Expert Systems with Applications, [Year].

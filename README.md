# Data and Results
This repository contains the real data in the Yangtze River and experimental results of the paper: 

**An exact approach to the all-electric ship scheduling problem with joint cargo transport and on-site energy refueling**

## Data
Port information and sailing distances between ports are provided.

* **port_information.csv**:
Ports are categorized by type, where Type 1 indicates a port on the main waterway and Type 0 indicates a port on a tributary.

*  **port_segment_distance.csv**:
Sailing distances between all adjacent ports (arc length of the realistic inland waterway topology).
 
*  **port_distance_matrix.csv**:
Distance matrix of all ports (arc length of the inland waterway shipping network).

## Results
Detailed results of *Section 7. Numerical experiments* are provided.

### Computational results

* **results_benchmark.xlsx**: results of benchmarking against Gurobi in *Section 7.2.1*.
* **results_BP.xlsx**: results of core algorithmic components in *Section 7.2.2--7.2.5*.

### Sensitivity analysis
* **sens_cargo.xlsx**: results of variable cargo transport demand in *Section 7.3.1*.
* **sens_battery.xlsx**: results of variable battery level in *Section 7.3.2*.


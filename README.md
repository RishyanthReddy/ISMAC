# ISMAC
Supporting data and analysis scripts for the paper "Intelligent Sustainable Multi-Agent Coordination (ISMAC): A Synergistic Algorithm for Resilient and Carbon-Efficient Supply Chain Management".

# Supporting Data for "Intelligent Sustainable Multi-Agent Coordination (ISMAC)"

This repository contains the simulation logs and analysis scripts supporting the findings of the paper, "Intelligent Sustainable Multi-Agent Coordination (ISMAC): A Synergistic Algorithm for Resilient and Carbon-Efficient Supply Chain Management." The data provided enables the full replication of all tables and figures presented in the manuscript. The repository is organized by experimental scenario, with raw `.csv` log files located in the `/data` subdirectories.

The analysis is performed using the Python scripts located in the `/analysis_scripts` folder. To reproduce the results, first install the required packages using `pip install -r analysis_scripts/requirements.txt`. Then, run the primary processing script `01_process_raw_logs.py` to parse the detailed event logs and generate an aggregated summary file. Subsequent scripts can then be run to generate the specific figures and tables, which will be saved in the `/generated_outputs` directory.

The core ISMAC simulation source code is not publicly available but may be requested from the corresponding author for academic, non-commercial research purposes. The data and analysis scripts herein are distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

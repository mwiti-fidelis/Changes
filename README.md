README
Hospital Data Monitoring & Archival System
Group 7
Project Overview
This system provides automated log management for hospital patient health metrics and resource usage data. It includes real-time data simulation, interactive log archival, and intelligent data analysis.

System Architecture
Components
Data Simulators - Generate real-time hospital data
Archive System - Manages log rotation and archival
Analysis Engine - Processes logs and generates reports
Reporting Module - Creates cumulative analysis reports
Directory Structure


# Hospital Data Directory

This directory contains all real-time and archived monitoring data from hospital devices.

## Subdirectories

- **active_logs/**:  
  Holds live log files currently being written to by simulators:
  - heart_rate.log
  - temperature.log
  - water_usage.log

-  *Archived_logs directory*
- **heart_data_archive/**:  
  Archived heart rate logs with timestamps (e.g., heart_rate_2024-06-18_15:22:10.log).

- **temp_data_archive/**:  
  Archived temperature logs with timestamps.

- **water_data_archive/**:  
  Archived water usage logs with timestamps.


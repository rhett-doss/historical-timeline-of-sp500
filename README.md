# S&P 500 Component History Builder

This repository showcases a Python-based solution designed to build a comprehensive historical view of the S&P 500 components. The script captures both the current constituents of the S&P 500 and its historical changes, sourced from Wikipedia and other datasets.

## Overview

### 1. **Data Acquisition and Preprocessing**:
- Fetches the current S&P 500 list from Wikipedia.
- Retrieves historical changes in the S&P 500 components.
- Loads an existing dataset containing the historical view of S&P 500 components.

### 2. **Changes Data Formatting**:
- Processes the fetched changes data, grouping them by date and formatting for easy integration with the historical dataset.

### 3. **Historic Data Updates**:
- Uses the processed changes data to update the historical dataset, ensuring a continuous and accurate representation of the S&P 500 components over time.

### 4. **Corporate Actions Integration**:
- Incorporates corporate actions, such as mergers and splits, into the historical dataset, refining its accuracy.

### 5. **Main Execution**:
- Orchestrates the above processes in sequence and provides the final output: an updated and comprehensive historical view of the S&P 500 components.

## Note to Viewers

This README is intended to provide a brief overview of the project's design and capabilities. The project is not meant for direct replication or use by others but rather as a showcase of my work in this domain.

---

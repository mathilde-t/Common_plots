# Histogram Comparison Script

## Overview
This script processes pickle files from the ColumnFlow workflow (specifically from the `mergeHistograms` step). It takes histogram data from different reconstruction levels and combines them into a single plot for comparison. 

## Features
- Reads multiple pickle files containing histograms from different reconstruction levels.
- Handles different binning structures.
- Normalizes all histograms so that their event counts are scaled between 0 and 1 on the y-axis.
- Generates a combined plot for visual comparison.

## Usage
1. Ensure you have the required pickle files from the ColumnFlow workflow.
2. Run the script with the paths to the relevant files as input.
3. View the output plot to compare the histograms.

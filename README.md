# conv_tdcs_paper
This repository consists data and its analysis for the paper "Frontopolar Cortex and Decision-Making: Null Effects of Conventional tDCS Stimulation"

# Reproducible Analysis for: "Frontopolar Cortex and Decision-Making: Null Effects of Conventional tDCS Stimulation"

This repository contains the complete dataset and analysis code for the study investigating the effects of cathodal tDCS over the right frontopolar cortex on decision-making performance.

## Abstract
The study tested whether suppression of right frontopolar cortex (FPC) activity via cathodal tDCS impairs decision-making performance. Twenty participants received either active or sham stimulation and performed a decision-making task. No significant differences were found between groups on accuracy, error rates, or missed responses, even after excluding outliers based on learning curves.

## Repository Structure
- `README.md` - This file, containing complete instructions
- `conv_tdcs_analysis_AT.ipynb` - Jupyter Notebook with full analysis code
- `conv_tdcs_data_AT.csv` - Raw behavioral data

## Data Description
The dataset contains the following variables:
- `Participant` - Unique participant identifier
- `Group` - Experimental condition (1 = active stimulation, 2 = sham stimulation)
- `Correct` - Number of correct responses
- `False` - Number of incorrect responses
- `no_button` - Number of missed responses (no button press)

## Requirements
The analysis was conducted using:
- Python 3.12.7 (Anaconda distribution)
- Jupyter Notebook 8.27.0
- pandas 2.2.2
- scipy 1.13.1
- pingouin 0.5.5
- numpy 1.26.4
- matplotlib 3.9.2
- seaborn 0.13.2

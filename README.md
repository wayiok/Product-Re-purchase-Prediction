# Directory Structure Documentation

## Overview
This document describes the structure and purpose of the directories and files in the project. Below is the hierarchical structure and explanation of each component.

## Project Structure

```text
Complete Code/
├── 1 - Data Analysis/
├── 2 - BERT and FNN/
│   ├── Models
│   ├── Pre-processing
│   ├── Submission
├── 3 - CASER/

REPORT
```

## Folder Descriptions

### 1. Complete Code
This is the root directory of the project containing all the project code.

#### a. 1 - Data Analysis
Includes jupyter notebook for data preprocessing and hit rate baseline provided by the kaggle competition.

#### b. 2 - BERT and FNN
Contains the code and outputs for the BERT + FNN experiments. It includes the full implementation, from early prototypes to the final approach. The initial notebooks were limited to 10,000–20,000 historical rows, while the final notebook scales up to 40,000 rows. 
- **Models**: Trained models and their checkpoints.
- **Pre-Processing**: Notebooks used for preprocessing, feature engineering, product embeddings, and generating historical negative samples. Last 5 notebooks are made by chunks of 20000 historical rows due to the large dataset and the CPU limitations. 
- **Submission**: Submission csv files with 10 predicted products, created from the various notebooks approaches. 

#### c. 3 - CASER
CASER model implementation and training notebooks. Scales to 80,000 rows of historical data and uses hard negative sampling.
## Notes
- The main project report summarizing the methodology, results, and analysis. The **REPORT** file is critical for understanding the overall project outcomes.
- The directory names and file organization aim to streamline project navigation and clarity.

For any questions or further clarifications, refer to the **REPORT** or contact the project team.

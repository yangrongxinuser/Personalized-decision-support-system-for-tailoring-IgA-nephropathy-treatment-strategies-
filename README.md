# -Optimal-Renal-Replacement-Therapy-for-ICU-Acute-Kidney-Injury-A-Network-Biomarker-Approach



This repository contains the code for the research paper titled "Optimal Renal Replacement Therapy for ICU Acute Kidney Injury: A Network Biomarker Approach". The project is divided into three main components: Autoencoder, Traditional Graph Feature Engineering, and Network Biomarker Construction.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Components](#components)
  - [Autoencoder](#autoencoder)
  - [Traditional Graph Feature Engineering](#traditional-graph-feature-engineering)
  - [Network Biomarker Construction](#network-biomarker-construction)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to optimize renal replacement therapy for ICU patients with acute kidney injury using network biomarkers. We employ a combination of autoencoders, traditional graph feature engineering techniques, and a novel network biomarker construction method to identify key biomarkers and enhance decision-making.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/renal-replacement-therapy.git
   ```
2. Navigate to the project directory:
  ```
   cd renal-replacement-therapy
  ```
3. Install the required dependencies:
 ```
   pip install -r requirements.txt
  ```

## Usage


1. Run the autoencoder model script:
   ```bash
   python autoencoder/model.py
   ```
2. Execute the graph feature extraction script:
  ```
   python graph_features/feature_extraction.py
  ```
3. Construct network biomarkers using:
 ```
   python network_biomarkers/biomarker_construction.py
  ```

## Project Structure

renal-replacement-therapy/
│
├── README.md
├── requirements.txt
├── autoencoder/
│   └── model.py
├── graph_features/
│   └── feature_extraction.py
└── network_biomarkers/
    └── biomarker_construction.py

## Components

# Autoencoder
The autoencoder/ directory contains the script for building and running the autoencoder model used for dimensionality reduction and feature extraction.
model.py: Defines and trains the autoencoder model.

# Traditional Graph Feature Engineering
The graph_features/ directory contains the script for extracting traditional graph features from the data.
feature_extraction.py: Extracts and analyzes graph-based features.

# Network Biomarker Construction
The network_biomarkers/ directory includes the script for constructing and analyzing network biomarkers.
biomarker_construction.py: Constructs network biomarkers from the extracted features.

## Dependencies

# Requirements for running the code
# These versions are based on those available in Google Colab
```
matplotlib==3.7.1
networkx==3.3
numpy==1.25.2
pandas==2.0.3
scipy==1.11.4
torch==1.9.0+cu102

```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License
This project is licensed under the MIT License

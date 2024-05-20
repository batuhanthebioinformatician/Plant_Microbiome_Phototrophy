# Plant_Microbiome_Phototrophy
This repository contains scripts for studying the role and genomic differences of phototrophic bacteria within plant microbiomes. It focuses on Aerobic Anoxygenic Phototrophic Bacteria (AAPB) and rhodopsin-based phototrophs in boreal and arctic regions, investigating phototrophic controls and key genomic differences.


## Project Description

**Title:** Comparative Genomics of Phototrophic Sphingomonas faeni strains


**Summary:**
Plant microbiomes play an essential role in enhancing plant nutrient uptake and improving stress resistance. This project focuses on a novel group of plant microbiomes: Aerobic Anoxygenic Phototrophic Bacteria (AAPB). These phototrophic bacteria utilize near-infrared light to produce chemical energy. This study aims to understand the role and genomic differences of phototrophic bacteria within plant microbiomes, particularly in boreal and arctic regions.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
  - [ANI Heatmap](#ani-heatmap)
  - [Core Pan Development](#core-pan-development)
  - [Photoreceptor Threshold](#photoreceptor-threshold)
  - [MDS Analysis](#mds-analysis)
  - [Combined Statistics - Mantel and PERMANOVA](#combined-statistics---mantel-and-permanova)
  - [PCoA Analysis](#pcoa-analysis)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/batuhanthebioinformatician/Plant_Microbiome_Phototrophy.git
    ```
2. Navigate to the directory of the script you want to run:
    ```bash
    cd Plant_Microbiome_Phototrophy/script_directory
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place the required data files at the specified path in the script.
2. Run the script:
    ```bash
    python script_name.py
    ```
3. The output will be displayed and can be saved as needed.

## Scripts

### ANI Heatmap

This script generates a heatmap for Average Nucleotide Identity (ANI) based on genomic data.

**Requirements:**
- pandas
- seaborn
- matplotlib


### Core Pan Development

This script plots the development of the core genome over the number of contigs.

**Requirements:**
- pandas
- matplotlib


### Photoreceptor Threshold

This script identifies sequences with more than selected % similarity to a reference sequence.

**Requirements:**
- biopython


### MDS Analysis

This script performs Multi-Dimensional Scaling (MDS) on a genetic dissimilarity matrix and visualizes the results.

**Requirements:**
- pandas
- numpy
- scikit-learn
- matplotlib


### Combined Statistics - Mantel and PERMANOVA

This script performs Mantel tests and PERMANOVA to compare distance matrices and test group differences.

**Requirements:**
- pandas
- numpy
- scipy
- scikit-bio


### PCoA Analysis

This script performs Principal Coordinates Analysis (PCoA) on a distance matrix and visualizes the results.

**Requirements:**
- pandas
- numpy
- matplotlib
- seaborn
- scikit-bio


## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License.

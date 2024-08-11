# Topsis Implementation in Python

This Python package implements the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) for multi-criteria decision-making.

## Features

- Calculate TOPSIS scores and rank alternatives.
- Input data via CSV files.
- Comprehensive validation of inputs.

## Installation

To install the package, use the following command:

```sh
pip install TOPSIS-JASHANDEEP-102218023
```

## Usage

Enter csv filename followed by .csv extentsion, then enter the weights vector with vector values separated by commas, followed by the impacts vector with comma separated signs (+,-) and result csv filename followed by .csv extension.

```sh
topsis  "sample.csv" "1,1,1,1" "+,-,+,+" "result.csv"
```


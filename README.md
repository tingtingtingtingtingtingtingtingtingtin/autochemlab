# AutoChemLab

A CLI tool to automatically fill out UCR's Organic Chemistry Reagent Tables.

## Description

AutoChemLab is designed to streamline the process of filling out reagent tables for organic chemistry labs at the University of California, Riverside. It supports both CLI interactions and PDF autofilling, making it easier for students to manage their lab assignments.

## Features

- Automatic extraction of chemical names from PDF fields
- Retrieval of CAS registry numbers (CASRNs) for chemicals
- Fetching molecular weights, boiling points, melting points, and densities from an online database
- Selection of using boiling point or melting point data for individual chemicals
- CLI interface for manual input and processing of chemical data
- PDF form autofilling with chemical properties

## Installation

To install the required dependencies, run the following command:

```shell
pip install -r requirements.txt
```

## Usage

### PDF
Run the script with a Reagents & Hazards PDF file as an argument:

```shell
python3 main.py <filename.pdf>
```

### No PDF
Run the script:

```shell
python3 main.py
```

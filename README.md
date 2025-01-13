# Project Title: Automated MCQ Generator and Retrieval System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


---

## Introduction

This project is designed to facilitate automated Multiple Choice Question (MCQ) generation and information retrieval. It includes tools for data preprocessing, MCQ generation, evaluation of retrieval strategies, and reasoning experiments to optimize the quality and relevance of generated content.

---

## Features

- **Data Preprocessing:** Clean and prepare data for analysis.
- **MCQ Generator:** Automatically generate MCQs based on input data.
- **Retriever:** Efficient information retrieval from preprocessed data.
- **Reasoning and Retrieval Strategies:** Experiment with different methods and evaluate their effectiveness.
- **Ragevaluation:** Evaluate the performance of generated content.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. Create Virtual Environment:
     ```bash
   python -m venv venv

3. Install dependencies:
     ```bash
   pip install -r requirements.txt

## Usage

1. Data Preprocessing
    
   Prepare and clean the raw data and store in vector database for further analysis.  
   ```bash
   cd src/datapreprocess

2. MCQ Generation
   
   Generate multiple-choice questions (MCQs) from the preprocessed data.
   ```bash
   cd src/mcqgenerator

3. Information Retrieval and Answer Extractor
   
   Retrieve relevant data using the defined retrieval strategies.
   ```bash
   cd src/retriver
  
4. Experiment
   
   Execute reasoning and retrieval experiments using Jupyter Notebook for detailed analysis.
   ```bash
   cd experiments/

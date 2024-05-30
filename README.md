# NeuralFinGPT

NeuralFinGPT is a comprehensive project aimed at downloading, preprocessing, and analyzing financial reports for MENA companies using NLP techniques. This repository includes code for creating a PostgreSQL database, fine-tuning the Mistral7b LLM using QLoRA, and implementing RAG algorithms for context creation to answer specific financial queries.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
NeuralFinGPT is designed to facilitate advanced financial data analysis for the MENA region by leveraging state-of-the-art NLP techniques and large language models.

## Features
- Download and preprocess financial reports.
- Create and manage a PostgreSQL database.
- Fine-tune Mistral7b LLM using QLoRA.
- Implement RAG algorithms for context-based queries.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/ranystephan/NeuralFinGPT.git
    ```
2. Navigate to the project directory:
    ```bash
    cd NeuralFinGPT
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the data collection script:
    ```bash
    jupyter notebook data_collection.ipynb
    ```
2. Fine-tune the model using:
    ```bash
    jupyter notebook fine-tuning_RAG_func.ipynb
    ```
3. Analyze financial data and run queries.

## Project Structure
- `data_collection.ipynb`: Script for downloading and preprocessing financial reports.
- `fine-tuning_RAG_func.ipynb`: Notebook for fine-tuning the language model.
- `neuralfingpt-draft1.pdf`: Initial project draft and documentation.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License
This project is licensed under the MIT License.
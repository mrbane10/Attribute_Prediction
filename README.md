# IndoML-2024-IIT-Bombay

This project tackles Attribute-Value Prediction from E-Commerce Product Descriptions as part of the IndoML 2024 competition organized by IIT Bombay. The aim is to predict product attributes from unstructured textual descriptions using advanced language model techniques.

## Overview

- **Objective**: Fine-tune a T5 model with quantization and LoRA for attribute prediction from unstructured product descriptions.
- **Methods**: 
  - **T5 Fine-Tuning**: Used T5 with 4-bit quantization and LoRA for efficient fine-tuning.
  - **Preprocessing Pipeline**: Built a JSONL-based pipeline to structure product data into input-output pairs, aiding in attribute prediction across hierarchical categories.
- **Results**: Achieved **81.04% item accuracy**, demonstrating precise attribute prediction across multiple product categories.

## Features

- **Efficient Model Fine-Tuning**: Leveraged 4-bit quantization and LoRA for computational efficiency without compromising accuracy.
- **Structured Preprocessing**: Developed a JSONL preprocessing pipeline to create clean input-output pairs for training.
- **Attribute Prediction**: Enhanced prediction accuracy for various e-commerce attributes in a hierarchical structure.

## Repository Structure

- **Copy_of_t5_baseline.ipynb**: Baseline notebook with initial T5 model setup.
- **IndoML_unsloth.ipynb**: Contains experiments and data preprocessing steps for attribute prediction.
- **indoml2024-baseline-modified.ipynb**: Modified baseline notebook with model optimizations.
- **t5_baseline.ipynb**: Core T5 model training and evaluation notebook.

## Getting Started

### Prerequisites

- **Python 3.8+**
- **Transformers Library**: For working with T5 and LoRA.
- **CUDA** (optional): For GPU acceleration if available.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IndoML-2024-IIT-Bombay.git
   cd IndoML-2024-IIT-Bombay
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks for data preprocessing and model training.

### Usage

- Open `t5_baseline.ipynb` to start with the model training and evaluation process.
- Use `IndoML_unsloth.ipynb` for data preprocessing to structure input-output pairs in JSONL format.

## Results

- **Item Accuracy**: The model achieved an accuracy of **81.04%** on test data, validating its performance on hierarchical attribute prediction.

## License

This project is licensed under the MIT License.

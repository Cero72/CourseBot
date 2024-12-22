# CourseBot

A specialized AI model trained to assist students with course-related questions, leveraging advanced fine-tuning techniques and optimized model architecture.

## Key Achievements

- **Model Optimization**: 
  - Optimized Mistral-7B model using QLoRA techniques and 4-bit quantization
  - Achieved 22.2% improvement in question-answering accuracy for course content
  - Implemented efficient inference pipeline with minimal computational overhead

- **Data Engineering**:
  - Synthesized comprehensive training corpus using Claude API and prompt chaining
  - Generated and validated 400+ high-quality Q&A pairs for fine-tuning
  - Ensured diverse coverage of course materials and concepts

- **Technical Innovation**:
  - Constructed robust context injection framework
  - Developed custom evaluation suite for response quality
  - Implemented reliable knowledge retention mechanisms
  - Ensured consistent course-specific responses

## Setup

Install required packages:
pip install transformers datasets accelerate bitsandbytes torch peft trl PyPDF2 scikit-learn pandas


## Project Structure

- `Base_model_inference.ipynb`: Base model inference implementation
- `Data Preprocessing.ipynb`: Data preparation pipeline
- `Training.ipynb`: Model training and fine-tuning
- `finetuned_model_inference.ipynb`: Fine-tuned model inference

## Requirements

- Python 3.11+
- PyTorch
- Transformers
- Other dependencies listed in installation command

## Usage

1. Run data preprocessing notebook
2. Execute training pipeline
3. Use inference notebooks for predictions

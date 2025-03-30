# LLM Fine-Tuning Projects

This repository contains various projects focused on fine-tuning Large Language Models (LLMs) which i am currently working on.  
I am still learning, and these projects are **a work in progress**. Some notebooks may not be fully complete and might contain errors. Contributions and feedback are welcome!

## Table of Contents

1. [Project Overview](#project-overview)
2. [Setup Instructions](#setup-instructions)
3. [Project Details](#project-details)
4. [Usage Guidelines](#usage-guidelines)
5. [Results and Evaluation](#results-and-evaluation)
6. [References and Resources](#references-and-resources)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

## Project Overview

This repository showcases diverse methodologies for fine-tuning Large Language Models (LLMs) on custom datasets:

- **Personal Dataset Fine-Tuning**: Standard techniques applied to user-specific datasets.
- **Finetuning Llama3 2 3B**: Advanced strategies using the Llama3 2 3B model with QLoRA quantization and Parameter-Efficient Fine-Tuning (PEFT).
- **LoRA Fine-Tuning**: Implementation of Low-Rank Adaptation for efficient model fine-tuning.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/LLM-Finetuning-Projects.git
   cd LLM-Finetuning-Projects
   ```

2. **Create a Virtual Environment (Recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Jupyter Notebook Setup:**
   Ensure Jupyter Notebook is installed:
   ```bash
   pip install notebook
   ```
   Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Project Details

### 1. Personal Dataset Fine-Tuning

- **Objective**: Adapt LLMs to user-specific data for personalized applications.
- **Methodology**: Utilizes standard fine-tuning techniques on custom datasets.
- **Dataset**: [https://huggingface.co/datasets/mlabonne/FineTome-100k]

### 2. Finetuning Llama3 2 3B

- **Objective**: Implement advanced fine-tuning using the Llama3 2 3B model.
- **Techniques**: Incorporates QLoRA quantization and PEFT for efficient training.


### 3. LoRA Fine-Tuning

- **Objective**: Explore Low-Rank Adaptation for parameter-efficient fine-tuning.
- **Methodology**: Applies LoRA techniques to adapt pre-trained models with reduced computational resources.


## Usage Guidelines

1. **Navigate to the Notebooks Directory:**
   ```bash
   cd notebooks
   ```

2. **Open the Desired Notebook:**
   Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Select the notebook of interest, e.g., `finetuning_personal_dataset.ipynb`.

3. **Follow the Notebook Instructions:**
   Each notebook contains detailed, step-by-step guidance. Execute the cells sequentially and adhere to the provided instructions.

## Results and Evaluation

### Personal Dataset Fine-Tuning

- **Metrics**: Achieved an accuracy of 92% on the validation set.
- **Sample Output**:
  ```
  Input: "Your sample input here"
  Output: "Model's generated response here"
  ```

### Finetuning Llama3 2 3B

- **Metrics**: Reduced perplexity score to 15.3.
- **Visualizations**: Include loss curves and accuracy charts.

## References and Resources

- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [QLoRA: Efficient Quantized Fine-Tuning](https://arxiv.org/abs/2305.14314)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Submit a pull request.

## License



---

**Note:** These projects are **still in progress** and may contain errors or incomplete implementations.  
This repository serves as a **learning resource** while I explore LLM fine-tuning. 🚀  

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to the open-source community and the developers of LLM fine-tuning techniques.

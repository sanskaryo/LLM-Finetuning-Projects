# LLM Fine-tuning Projects

This repository contains three different approaches to fine-tuning Large Language Models (LLMs):

1. [Personal Dataset Fine-tuning](finetuning_personal_dataset.ipynb)
2. [Mistral with QLora and PEFt](Fine_Tuning_with_Mistral_QLora_PEFt.ipynb)
3. [LoRA Fine-tuning](LORA_FineTuning.ipynb)

## Overview

This collection demonstrates different techniques for fine-tuning LLMs on custom datasets:

- **Personal Dataset Fine-tuning**: Fine-tune models on your own dataset using standard techniques
- **Mistral with QLora and PEFt**: Advanced fine-tuning using Mistral model with QLora quantization and PEFt parameter-efficient fine-tuning
- **LoRA Fine-tuning**: Parameter-efficient fine-tuning using Low-Rank Adaptation

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/llm-finetuning-projects.git
cd llm-finetuning-projects
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

- `finetuning_personal_dataset.ipynb`: Standard fine-tuning approach
- `Fine_Tuning_with_Mistral_QLora_PEFt.ipynb`: Advanced fine-tuning with Mistral
- `LORA_FineTuning.ipynb`: LoRA-based fine-tuning
- `requirements.txt`: Project dependencies
- `README.md`: This file

## References and Resources

### Papers and Articles
- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314)
- [PEFT: Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2203.02155)

### Hugging Face Resources
- [PEFT Library](https://huggingface.co/docs/peft)
- [Transformers Library](https://huggingface.co/docs/transformers)
- [Mistral Models](https://huggingface.co/mistralai)
- [LoRA Implementation](https://huggingface.co/docs/peft/conceptual_guides/lora)

### Tutorials and Guides
- [Hugging Face Fine-tuning Guide](https://huggingface.co/docs/transformers/training)
- [LoRA Fine-tuning Tutorial](https://huggingface.co/docs/peft/task_guides/sequence_classification_lora)
- [QLoRA Implementation Guide](https://github.com/artidoro/qlora)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Hugging Face for their excellent libraries and documentation
- Mistral AI for their open-source models
- The research community for their groundbreaking papers on efficient fine-tuning techniques 
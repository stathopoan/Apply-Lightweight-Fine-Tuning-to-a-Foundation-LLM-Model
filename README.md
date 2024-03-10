# Apply-Lightweight-Fine-Tuning-to-a-Foundation-LLM-Model
Lightweight fine-tuning is one of the most important techniques for adapting foundation models, because it allows you to modify foundation models for your needs without needing substantial computational resources.  In this project, we will apply parameter-efficient fine-tuning using the Hugging Face peft library.
## Project Summary
In this project, you will bring together all of the essential components of a PyTorch + Hugging Face training and inference process. Specifically, you will:

- Load a pre-trained model and evaluate its performance
- Perform parameter-efficient fine tuning using the pre-trained model
- Perform inference using the fine-tuned model and compare its performance to the original model

## Key Concepts
Hugging Face PEFT allows you to fine-tune a model without having to fine-tune all of its parameters.

Training a model using Hugging Face PEFT requires two additional steps beyond traditional fine-tuning:

- Creating a PEFT config
- Converting the model into a PEFT model using the PEFT config

Inference using a PEFT model is almost identical to inference using a non-PEFT model. The only difference is that it must be loaded as a PEFT model.

### Project run

To be able to run the project just install all libraries required in the requirements.tx file and run jupyter notebook
GPU use is highly suggested

All code in ipynb file
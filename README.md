# Overview

Quantum GPT: a LLM for text generation using using QML based on GPT2-small.

We replace the key, query and value matrices with variational quantum circuits effectively reducing the number of trainable parameters

# Model card

Total number of parameters: 117M

Number of quantum parameters: 65k

# Benchmark results

| **Dataset** | LAMBADA 10k (first 10k symbols) |
|:-----------:|:-------------------------------:|
|  **Metric** |               PPL               |
|  **Score**  |              422.00             |


# Availible models

Current best model was trained with OpenWebText-100k dataset for 30 epochs. You can download the weights [here](https://drive.google.com/file/d/1x_Ro5Kta-R5yDCCnuaPjNZ_b6TNIs7_T/view?usp=drive_link)

![train plot](100k_loss.pdf)

Currents requirements are at least 20GB VRAM for training and 12GB VRAM for inference
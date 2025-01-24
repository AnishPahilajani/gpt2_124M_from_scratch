# GPT-2 Training from Scratch

This project involves training GPT-2 (124M parameters) from scratch using PyTorch. The model was trained using a fineweb-edu dataset and optimized for performance with multi-GPU support.

## Key Features
- **Framework**: PyTorch
- **Architecture**: GPT-2 124M trained from scratch
- **Multi-GPU Training**: Leveraged PyTorch Distributed Data Parallel (DDP)
- **Dataset**: fineweb-edu dataset

## Architecture
Below is a visual representation of the GPT-2 124M architecture:



## Training Process
1. **Data Preparation**: Preprocessed the dataset to ensure compatibility with the GPT-2 tokenizer.
2. **Model Initialization**: Implemented GPT-2 architecture and initialized weights.
3. **Optimization**: Used Adam optimizer with learning rate scheduling for efficient training.
4. **Multi-GPU Setup**: Enabled DDP for scalable training.

## Results
Training performance and loss curve:

![Training Plot](loss accuracy plot.png)

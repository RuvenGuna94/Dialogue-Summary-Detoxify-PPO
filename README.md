# Dialogue-Summary-remove-toxic-text-PPO

This repository contains a project for removing toxic text using a Proximal Policy Optimization (PPO) approach with Hugging Face and PyTorch. The project aims to fine-tune a model to effectively summarize dialogues while detoxifying the text.

## Features
- Fine-tuning a model using Proximal Policy Optimization (PPO) for text detoxification.
- Leveraging the Hugging Face library for pre-trained model utilization and customization.
- Implementation of key techniques for toxic text detection and summarization:
  - **Reward modeling** for aligning model outputs with detoxification goals.
  - **Policy optimization** to enhance generative text quality.
- Demonstrates integration of reinforcement learning for language model tuning.
- Practical examples for:
  - Identifying and removing toxic content from text data.
  - Generating dialogue summaries while ensuring the output is non-toxic.
- Modular and reusable code structure for experimentation with different datasets and evaluation metrics.

## Project Structure

- **`PPO_detoxify.ipynb`**: Jupyter Notebook containing the implementation of the PPO algorithm for text detoxification.
- **`requirements.txt`**: List of dependencies needed to run the project.
- **Other Files**: Additional scripts or data files can be added as needed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RuvenGuna94/Dialogue-Summary-remove-toxic-text-PPO.git
   cd Dialogue-Summary-remove-toxic-text-PPO
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook to explore the code:
   ```bash
   jupyter notebook PPO_detoxify.ipynb
   ```

## Usage

Open the notebook and execute the cells step-by-step to train and evaluate the PPO-based detoxification model.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License. 

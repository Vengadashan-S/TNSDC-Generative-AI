# TNSDC-Generative-AI

## Overview
This project uses GAN(Generative Adversarial Network) to convert given text into a compelling story. The AI algorithm processes the input text and generates a narrative structure, complete with characters, plot development, and a cohesive storyline.

## Installation
1. Clone the repository:
2. git clone https://github.com/Vengadashan-S/TNSDC-Generative-AI.git
3. Navigate to the project directory:


## Libraries Used
The code utilizes the following libraries:
1. torch: This library is used for tensor computation and deep learning models in PyTorch.
2. transformers: This library provides state-of-the-art natural language processing models, including GPT-2, along with pre-trained models and tokenizers.
3. TensorFlow: This library is used for machine learning and deep learning tasks, providing tools for building and training neural networks.
4. TensorLayer: TensorLayer is a high-level deep learning library built on top of TensorFlow, offering simplified APIs for creating and training neural networks.

## Code Functionality
- The code utilizes the Transformers library to load a pre-trained GPT-2 model and tokenizer.
- It defines a function `generate_story(prompt, max_length=500, temperature=0.9)` to generate a story based on the user input prompt.
- The `main()` function interacts with the user, prompting them to input a starting prompt for the story or to quit the program.
- Upon receiving a prompt, it generates a story using the GPT-2 model with a specified temperature, prints the generated story, and displays its approximate word count.
- The program continues to prompt the user for input until they choose to quit.
- The code facilitates the automatic generation of creative narratives, allowing users to explore story generation based on their provided prompts.

## Usage
1. Start the generative AI model: 
2. Follow the on-screen instructions to input prompts and generate stories.

## Example
Input Prompt:
Once upon a time, in a faraway land, there lived a brave knight named Sir Lancelot.

Generated Story:
Sir Lancelot, the valiant knight of Faraway Land, stood tall amidst the ancient oaks, his armor gleaming under the golden sun. With every step, he echoed the tales of old, a beacon of hope in a world shrouded in darkness. His journey was not just a quest for glory, but a testament to the unwavering spirit of courage and honor that burned within him.

## Model Training
If you're interested in training the AI model further or fine-tuning it for specific storytelling styles, refer to the `train_model.py` script and the provided training data.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

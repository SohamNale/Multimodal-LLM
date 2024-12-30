# Multimodal-LLM

This project demonstrates a multimodal Language Learning Model (LLM) using Llama 3.2 Vision. The model can take both image and text as input and provide text output. The model is run locally using Ollama and keeps context history to handle follow-up questions.

## Features

- Multimodal input: Accepts both images and text.
- Context history: Maintains conversation history for coherent follow-up responses.
- Local deployment: Runs the Llama 3.2 Vision model locally using Ollama.
- Gradio interface: Provides a user-friendly interface for interaction.

## Requirements

- Python 3.6+
- `requests` library
- `gradio` library
- Ollama (for running the Llama 3.2 Vision model locally)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/SohamNale/Multimodal-LLM.git
    cd Multimodal-LLM
    ```

2. Install the required Python packages:
    ```sh
    pip install requests gradio
    ```

3. Ensure Ollama is installed and running on your local machine.

## Usage

1. Start the Ollama server on your local machine.

2. Run the  script:
    ```sh
    python vision_llm.py
    ```

3. Open the provided Gradio interface in your web browser.

4. Interact with the assistant by uploading images and typing text queries.

## Code Overview

- : Interacts with the Ollama API to get responses from the Llama 3.2 Vision model.
- : Handles user messages, updates the conversation history, and gets responses from the model.
- : Sets up the Gradio interface for user interaction.

## Example

1. Start the script:
    ```sh
    python vision_llm.py
    ```

2. Open the Gradio interface in your browser.

3. Upload an image and type a query related to the image.

4. Receive a response from the assistant.

## Acknowledgements

- [Gradio](https://gradio.app/) for the user interface.
- [Ollama](https://ollama.com/) for running the Llama 3.2 Vision model locally.

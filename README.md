# Gemini: Open Source Large Language Model
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/downloads/)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)

Gemini LLM Application is an open-source project that leverages state-of-the-art language models for text generation and image description. This project utilizes the Gemini API key to enable powerful natural language processing capabilities. Whether you're interested in creative text generation or generating descriptive captions for images, Gemini has you covered.

To see training of different neural network architectures click below

Automatic Text Generation: https://github.com/CODING-Enthusiast9857/Automatic_Text_Generation

## Features

- **Text Generation:** Generate human-like text for various applications, including creative writing, code completion, and more.

- **Image Description:** Leverage Gemini's language model to automatically generate descriptive captions for images.

## Getting Started

### Prerequisites

- Python 3.6+
- Gemini API Key (Get yours [here](https://makersuite.google.com/app/apikey))

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/CODING-Enthusiast9857/Gemini_LLM_Application.git
    cd Gemini_LLM_Application
    ```
    
2. Set your Gemini API Key:

    Store `<your_gemini_api_key>` in variable name GOOGLE_API_KEY and save it in `.env` file with your actual Gemini API key.

### Usage

1. Run the text generation script:

    ```bash
    streamlit run app.py
    ```

2. Run the image description script:

    ```bash
    streamlit run vision.py 
    ```

## Contributing

Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to OpenAI for providing the Gemini API.

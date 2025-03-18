# English-to-Swahili Translator

## Overview
This is a simple Python script that translates English text into Swahili using a pre-trained neural machine translation model from the [Helsinki-NLP](https://huggingface.co/Helsinki-NLP) project. The script utilizes the `transformers` library by Hugging Face and the `torch` library for running the model.

## Features
- Uses the `Helsinki-NLP/opus-mt-en-sw` model for translation.
- Accepts user input interactively and provides instant Swahili translations.
- Simple and lightweight implementation using PyTorch and Transformers.

## Prerequisites
Ensure you have the following installed before running the script:
- Python (>=3.7)
- PyTorch (`torch`)
- Transformers (`transformers`)

## Installation
1. Clone or download this repository.
2. Install the required dependencies by running:
   ```sh
   pip install torch transformers
   ```

## Usage
1. Run the script:
   ```sh
   python script.py
   ```
2. Enter English text to translate.
3. Type `exit` to quit the program.

## Code Explanation
- The script loads the `Helsinki-NLP/opus-mt-en-sw` model and tokenizer.
- It defines a `translate()` function to convert English text into Swahili.
- It runs an interactive loop where users can input text, receive translations, and exit when desired.

## Example
```sh
🔠 English-to-Swahili Translator (Type 'exit' to quit) 🔠

Enter English text: Hello, how are you?
Swahili Translation: Habari, unaendeleaje?

Enter English text: Thank you very much.
Swahili Translation: Asante sana.

Enter English text: exit
Goodbye! 👋
```

## License
This project is open-source and licensed under the MIT License.

## Acknowledgments
Special thanks to Helsinki-NLP and Hugging Face for providing pre-trained translation models.


# Toy Translator from Italian to English

This is a simple toy translator project that translates Italian text to English using machine translation models. The project utilizes neural machine translation and evaluates its performance using various metrics.

## Project Overview

The project is designed to demonstrate the usage of machine translation models for translating Italian text to English. Two primary models have been employed: a Transformer-based model and a GRU-based model. The primary objectives include:

1. Translation of Italian sentences to English.
2. Evaluation of translation quality using metrics such as BLEU, WER (Word Error Rate), TER (Translation Edit Rate), and METEOR.

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset for training and evaluation.
- `models/`: Stores the machine translation models.
- `scripts/`: Includes Python scripts for data preprocessing, model training, and evaluation.
- `README.md`: This file.
- `requirements.txt`: Lists the project dependencies.
- `translator_app.py`: A simple web application for using the translation models.

## Getting Started

Clone the repository:

```bash
   git clone https://github.com/your-username/toy-translator.git
   cd toy-translator
```

## Usage

1. Enter an Italian sentence into the web application.
2. Choose the translation model you want to use (Transformer or GRU).
3. Click the "Translate" button to see the English translation.

## Evaluation

The translation quality is assessed using the following metrics:

- **BLEU (Bilingual Evaluation Understudy):** Measures the similarity between the predicted and reference translations.
- **WER (Word Error Rate):** Measures the number of word insertions, deletions, and substitutions in the translation.
- **TER (Translation Edit Rate):** Measures the number of editing operations required to change the translation to the reference.
- **METEOR (Metric for Evaluation of Translation with Explicit ORdering):** Evaluates translation quality considering synonyms and stemming.

## Contributing

Contributions to this project are welcome. Please open an issue to discuss potential changes or improvements.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

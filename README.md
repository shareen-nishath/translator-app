# 🌍 Universal Language Translator

## 📌 Project Description

The Universal Language Translator is an AI-powered application that translates text between multiple languages using the pretrained Hugging Face NLLB-200 Distilled 600M model.

The application provides a simple, interactive interface built with Gradio, allowing users to select their source and target languages and translate text instantly.

## 🎯 Features

* Supports translation between many languages.
* Includes English, Tamil, Hindi, French, German, Spanish, Arabic, Japanese, and more.
* Simple and user-friendly interface.
* Source and target language selection.
* Real-time text translation.
* Uses a pretrained multilingual NLP model.
* Runs in Google Colab or a compatible Python environment.

## 🛠️ Technologies Used

* Python
* Hugging Face Transformers
* NLLB-200 Distilled 600M
* PyTorch
* Gradio
* SentencePiece

## 🤖 Model Information

**Model:** `facebook/nllb-200-distilled-600M`

**Hugging Face Model Page:**
https://huggingface.co/facebook/nllb-200-distilled-600M

NLLB stands for No Language Left Behind. It is a multilingual machine translation model designed to translate between many languages.

## 📂 Project Structure

```text
Universal-Language-Translator/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Universal-Language-Translator
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

The Gradio application will provide a local URL to open the translator.

## 🚀 How to Use

1. Launch the application.
2. Select the source language.
3. Select the target language.
4. Enter the text you want to translate.
5. Click the Translate button.
6. View the translated text.

## 💻 Hardware Requirements

* Python 3.10 or a compatible version supported by the dependencies.
* Minimum 8 GB RAM recommended.
* GPU recommended for faster inference.
* Internet connection for the initial model download.

## ⚠️ Limitations

* The application supports only the languages configured in its language list.
* Translation quality varies by language.
* Some languages and dialects may not be supported.
* Very long inputs may require splitting into smaller sections.
* This pretrained model is intended primarily for research use and is not licensed for unrestricted commercial use.

## 📜 License

Review the model's license and terms before redistributing the model or using it in other applications.

## 👩‍💻 Author

Shareen Nishath

AI & Data Science Student

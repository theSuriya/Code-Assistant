# GenXai - Your Personal Coding Assistant

## Overview

GenXai (Generation Expert AI) is a powerful tool designed to assist with programming-related questions. Whether you need help fixing errors, understanding code, or refining your questions, GenXai is here to help. Built using Streamlit and the Gemini API, this project provides an interactive coding assistant that can boost your productivity and enhance your coding experience.

## Features

- **Error Fixing:** Automatically detects and suggests fixes for coding errors.
- **Code Assistance:** Helps you understand complex code and provides explanations.
- **Interactive Chat:** Engage in a productive conversation with GenXai to refine your coding questions and solutions.
- **Streamlit Interface:** User-friendly interface built with Streamlit.
- **Gemini API Integration:** Leverages the power of the Gemini API for natural language processing.

## Demo

here is an Demo of an [App](https://huggingface.co/spaces/suriya7/Code-Assistant)

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
```bash
   git clone https://github.com/theSuriya/Code-Assistant.git
```
After cloning the repo locate the project dir and run the following command in the terminal

2. **Google API KEY**:
Go to this site to generate api key [HERE](https://aistudio.google.com) You can see left side generate api thn click and copy. Once you have the api key, locate the .env file in your project directory. Open it and paste your api key like this:
  ```dotenv
  GOOGLE_API_KEY = "paste the api key here"
  ```

3. **Install the dependencies:**
 ```bash
     pip install -r requirements.txt
```

4. **Run the Streamlit app:**
```bash
   streamlit run app.py
```
## Usage

- Open your web browser and go to http://localhost:8501 to interact with GenXai.
- Enter your coding queries, and let GenXai assist you with suggestions, fixes, and explanations.

## Contact
For any questions or suggestions, feel free to reach out:

- Suriya
- [Mail](mailto:thesuriya3@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/suriya-s-83b25524a)

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Google Gemini API](https://developers.google.com/gemini)
- [Hugging Face Spaces](https://huggingface.co/spaces)


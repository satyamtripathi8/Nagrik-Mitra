# Nagrik Mitra

## Overview
**Nagrik Mitra** is a digital initiative aimed at promoting constitutional literacy among citizens. It is a part of the project **'Let’s Learn Constitution in a Simpler Manner - Citizen Perspective'**, which seeks to simplify legal concepts and enhance public understanding of the Indian Constitution.

This platform integrates **gamification, multilingual support, and AI-powered tools** to make learning about the Constitution engaging and accessible.

## Features
- **Simplified Constitutional Articles**: Key articles are rewritten in an easy-to-understand manner.
- **Gamified Learning**: Interactive games like **Spin a Wheel, Board Games, and Monopoly-style games** to test and reinforce knowledge.
- **Multilingual Support**: Content is available in multiple Indian languages.
- **AI-powered Chatbot**: Uses **fine-tuned LLaMA 2 and T5 models** to answer user queries related to constitutional laws.
- **Legal Document Analysis**: Utilizes NLP models for summarizing and explaining legal documents.

## Model and Dataset
We leverage state-of-the-art NLP models fine-tuned on Indian constitutional texts:
- [Fine-tuned LLaMA 2-7B Chat](https://huggingface.co/satyamtripathii/Fine_tunned_LLaMa2-7b-chat-hf)
- [Fine-tuned T5 Model](https://huggingface.co/satyamtripathii/fine_tunned_T5)
- [Laws and Constitution of India Dataset](https://huggingface.co/datasets/satyamtripathii/Laws_and_Constitution_of_India)

## Tech Stack
- **Frontend**: Flask
- **Backend**: Python (Flask)
- **AI Models**: Hugging Face Transformers (LLaMA, T5)
- **Database**: yet to do 
- **Cloud Hosting**: Hugging Face Spaces

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/satyamtripathii/NagrikMitra.git
   cd NagrikMitra
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Contribution
We welcome contributions! Feel free to raise issues, suggest improvements, or submit PRs to enhance **Nagrik Mitra**.

## License
This project is licensed under the MIT License.


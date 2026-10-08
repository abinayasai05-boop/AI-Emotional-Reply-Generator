# 🤖 AI Emotional Reply Generator

An AI-based application that detects the emotional tone of a user's message and generates a suitable emotional reply.

The project uses a pretrained NLP emotion classification model to identify emotions such as **joy, sadness, anger, fear, surprise, disgust, and neutral**.

## 🚀 Features

- 🎭 Emotion detection
- 📊 Emotion confidence score
- 🤖 Automatic emotional reply generation
- 💬 Interactive Google Colab interface
- 😊 Supports multiple emotions
- 🧠 Uses a pretrained Transformer model
- 🗑️ Clear input option
- ⚡ Runs directly in Google Colab

## 🧠 Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- PyTorch
- ipywidgets
- NLP
- Emotion Classification

## 🎯 Supported Emotions

The system can identify:

- 😊 Joy
- 😢 Sadness
- 😡 Anger
- 😨 Fear
- 😮 Surprise
- 🤢 Disgust
- 😐 Neutral

## ⚙️ How It Works

```text
User Message
     ↓
Text Input
     ↓
AI Emotion Detection
     ↓
Emotion Classification
     ↓
Confidence Score
     ↓
Emotional Reply Generation
     ↓
AI Response
```

## 📌 Example

### Input

```text
I studied so hard and finally passed my exam!
```

### Output

```text
Detected Emotion: JOY

Confidence: 98%

AI Emotional Reply:
That's wonderful to hear! I'm really happy for you.
```

## 🛠️ Installation

Run the following command in Google Colab:

```python
!pip -q install transformers torch sentencepiece ipywidgets
```

Then run the main Python code provided in the notebook.

## ▶️ How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Install the required libraries.
4. Run the AI emotion detection code.
5. Run the interactive interface.
6. Enter a message in the text box.
7. Click **Generate Emotional Reply**.
8. View the detected emotion, confidence score, and generated reply.

## 💡 Example Inputs

```text
I got my dream job today!
```

```text
I failed my exam and I feel terrible.
```

```text
My friend betrayed me and I'm really angry.
```

```text
I'm nervous about my interview tomorrow.
```

```text
I can't believe I won the competition!
```

## 🌟 Applications

This project can be used as a foundation for:

- AI chatbots
- Customer support systems
- Student support applications
- Emotional communication assistants
- Feedback analysis
- Social media sentiment applications
- Mental wellness conversation interfaces

## ⚠️ Disclaimer

This project is an educational AI application. Emotion detection is based on patterns in text and may not always correctly understand a person's actual emotional state. The generated replies should not be considered professional medical or psychological advice.

## 🔮 Future Improvements

- Add more emotions
- Generate more personalized replies
- Add voice input
- Add text-to-speech
- Add multilingual emotion detection
- Add conversation memory
- Create a web application
- Add sentiment analysis
- Add real-time chat functionality
- Deploy the application online

## 👩‍💻 Project

**Project Title:** AI Emotional Reply Generator

**Platform:** Google Colab

**Domain:** Artificial Intelligence / Natural Language Processing

**Type:** TSA Application Project

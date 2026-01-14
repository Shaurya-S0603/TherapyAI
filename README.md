# 🧠 Therapy AI -- Emotional Support System

Therapy AI is a **Python-based emotional support AI** designed for
**teens and young adults**.\
It provides **empathetic, non-judgmental conversations** through **text
and speech**, while strictly following **ethical, safety, and privacy
guidelines**.

> ⚠️ **Important Notice**\
> This system is **NOT a licensed therapist** and does **NOT provide
> medical, psychological, or clinical advice**.

------------------------------------------------------------------------

## 🌱 Purpose

The goal of Therapy AI is to: - Offer emotional support in moments of
stress or overwhelm - Help users feel heard and understood - Encourage
healthy reflection and coping - Promote reaching out to trusted people
or professionals when needed

This project is built as a **support companion**, not a replacement for
therapy.

------------------------------------------------------------------------

## ✨ Features

-   💬 Text-based conversations
-   🎤 Speech input and speech output
-   🧠 Emotion-aware responses
-   🤍 Empathy-first conversation flow
-   🚨 Crisis & self-harm detection with responsible escalation
-   🧾 Short-term and long-term memory (privacy-safe)
-   🔒 Ethics-first and safety-first architecture
-   🧩 Modular, scalable Python design

------------------------------------------------------------------------

## 🎯 Target Audience

-   Teenagers (13--19)
-   Young adults (20--30)
-   Individuals experiencing:
    -   Stress
    -   Anxiety
    -   Loneliness
    -   Emotional overwhelm
    -   Academic or social pressure

------------------------------------------------------------------------

## 🏗️ System Architecture

User Input (Text / Speech)\
↓\
Emotion Detection\
↓\
Safety & Crisis Check\
↓\
Therapy Logic (Empathy Engine)\
↓\
Response Generation\
↓\
Text / Speech Output

------------------------------------------------------------------------

## 📁 Project Structure

therapy_ai/ ├── src/ │ ├── input/ \# Text & speech input handlers │ ├──
output/ \# Text & speech output handlers │ ├── nlp/ \# Emotion & intent
detection │ ├── therapy/ \# Empathy & response logic │ ├── safety/ \#
Crisis detection & escalation │ ├── memory/ \# Conversation memory │ ├──
interfaces/ \# CLI / API / GUI │ └── main.py \# Application entry point
│ ├── data/ \# Datasets (raw & processed) ├── models/ \# Trained models
& prompt templates ├── docs/ \# Ethics, safety & policy documents ├──
scripts/ \# Training & preprocessing scripts ├── tests/ \# Unit and
safety tests ├── requirements.txt └── LICENSE

------------------------------------------------------------------------

## 📊 Dataset Usage

Public mental health and emotion datasets are used strictly for: -
Emotion classification - Risk detection - Language pattern understanding

Statistical datasets are **never used for response generation**.

------------------------------------------------------------------------

## 🔒 Ethics & Safety

-   No diagnosis
-   No medical advice
-   No therapist impersonation
-   Mandatory crisis escalation
-   Privacy-first data handling

------------------------------------------------------------------------

## 🚀 Getting Started

``` bash
git clone https://github.com/your-username/therapy-ai.git
cd therapy-ai
pip install -r requirements.txt
python src/main.py
```

------------------------------------------------------------------------

## 🧪 Testing

``` bash
pytest tests/
```

------------------------------------------------------------------------

## 📜 License

MIT License

------------------------------------------------------------------------

## ❤️ Disclaimer

Therapy AI provides **emotional support only**.\
If you are in immediate danger, please contact local emergency services
or a mental health professional.

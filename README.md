**ToxiFix: Emotionally Intelligent Toxic Comment Classifier**

ToxiFix is an AI-powered system designed to identify and transform toxic comments in real time. By combining transformer-based classification, paraphrasing through prompt-tuned language models, and reinforcement learning from human feedback (RLHF), ToxiFix aims to foster safer, more inclusive online communication.

🔗 Live Demo: Try it on Hugging Face

🔍 Overview
ToxiFix works in three stages:

Toxicity Detection – Identifies harmful language across multiple languages.

Comment Paraphrasing – Rewrites toxic content using emotionally intelligent language models.

RLHF Optimization – Improves rewriting using custom reward functions based on empathy, toxicity reduction, and semantic similarity.

🧠 Features
Multilingual toxic comment classification (English, Hindi, Hinglish)

Emotionally aware paraphrasing with few-shot prompting

Toxicity, bias, and empathy scoring using fine-tuned evaluation models

Custom RLHF reward engine to refine outputs

Real-time inference deployed via Gradio

💻 Tech Stack
Transformers: BERT, RoBERTa, XLM-RoBERTa

Paraphrasing: Prompt-tuned Granite 3.2-2B

Evaluation Models: Emotion-BERT, Sentence-BERT

Backend: Python, Hugging Face, Gradio

RLHF: Custom reward functions and fine-tuning loop

📊 Model Performance
Model	Accuracy	F1 Score	AUC
BERT	92.53%	92.79%	0.9810
DistilBERT	91.32%	91.39%	0.9553
XLM-RoBERTa	90.17%	90.23%	0.9638

📁 Datasets Used
Jigsaw Multilingual Toxic Comment Classification

YouTube Toxic Comments Dataset

Manually scraped multilingual YouTube comments

RLHF reward dataset curated via expert labeling

🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/toxifix.git  
cd toxifix  
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt  
Run the app:

bash
Copy
Edit
python app.py  
📈 Evaluation Metrics
Toxicity Score – Based on fine-tuned classifier

Bias Detection – Flagging potential group-based bias

Semantic Similarity – Using Sentence-BERT

Empathy Score – Based on fine-tuned Emotion-BERT

RLHF Reward Score – Weighted combination for model tuning

👥 Team
Jahnavi Chintakindi – Toxicity classification, model integration

Poojitha Ganta – Paraphrasing module, prompt engineering

Ramya Rangaraju – RLHF reward modeling and architecture

🔮 Future Work
Browser extension integration (YouTube, Gmail, Twitter)

Expansion of RLHF dataset with public contributions

Real-time toxicity detection and rewriting API

📄 License
MIT License


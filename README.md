ToxiFix: Emotionally Intelligent Toxic Comment Classifier
ToxiFix is a transformer-based NLP system designed to detect and paraphrase toxic comments in real time. It combines BERT-based classifiers, paraphrasing using LLMs, and reinforcement learning from human feedback (RLHF) to promote safer online spaces.

🚀 Live Demo: Try it on Hugging Face : https://janviml-toxic-comment-classifier.hf.space/

🧠 Key Features
Multilingual Toxic Comment Detection using BERT, RoBERTa, and XLM-RoBERTa

Emotionally Aware Paraphrasing with few-shot prompt engineering

RLHF-Based Fine-Tuning with empathy, bias, and semantic metrics

Real-Time Evaluation on toxicity, empathy, and semantic similarity

🛠 Tech Stack
Python 3.8+

Hugging Face Transformers

Gradio (Frontend UI)

Sentence-BERT, Emotion-BERT (Evaluation)

Granite 3.2-2B (Paraphrasing model)

RLHF custom scoring mechanism

📊 Datasets
Jigsaw Multilingual Toxic Comment Classification

YouTube Toxic Comments Dataset

Manually scraped multilingual YouTube comments

Human feedback reward dataset for RLHF training

🧪 Model Performance (Highlights)
Model	Accuracy	F1 Score	AUC
BERT	92.53%	92.79%	0.9810
DistilBERT	91.32%	91.39%	0.9553
XLM-RoBERTa	90.17%	90.23%	0.9638

🧬 Architecture Pipeline
Stage 1: Detect Toxic Comments using Transformers

Stage 2: Paraphrase Toxic Text via prompt-tuned LLMs

Stage 3: Evaluate Rewritten Text (toxicity, bias, empathy)

Stage 4: Refine using Reinforcement Learning from Human Feedback

Stage 5: Deployed on Hugging Face with real-time moderation

📈 Evaluation Metrics
Toxicity Score

Bias Detection

Semantic Similarity

Empathy Score

RLHF-based Reward Optimization

👥 Contributors
Jahnavi Chintakindi – Lead Developer, Classification Pipeline, Evaluation

Poojitha Ganta – Paraphrasing, Prompt Engineering, Metric Design

Ramya Rangaraju – RLHF Implementation, Deployment Architecture

📌 Future Enhancements
Chrome extension and API integrations for platforms like Gmail and YouTube

Expanded multilingual support and fairness audits

Integration of real-time user feedback into RLHF loop

📃 License
This project is licensed under the MIT License.


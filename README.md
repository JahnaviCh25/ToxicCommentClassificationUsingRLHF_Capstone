**ToxiFix: An AI-Powered Multilingual Toxic Comment Classifier and Rewriter** 

ToxiFix is an advanced NLP system designed to identify and neutralize toxic language across multiple languages. This project leverages transformer-based classification models, prompt-tuned paraphrasing, and reinforcement learning from human feedback (RLHF) to transform harmful content into constructive communication—without compromising intent.

📍 Live Demo: Launch the App on Hugging Face Spaces : https://janviml-toxic-comment-classifier.hf.space/

🧩 Project Summary
In an era of increasingly polarized digital discourse, detecting and rephrasing toxic comments is not just a technical challenge—but a social necessity.

**ToxiFix follows a five-stage pipeline:**
Detection: Identifies toxic content using state-of-the-art multilingual classifiers.
Paraphrasing: Rewrites toxic comments through prompt-engineered LLMs.
Evaluation: Scores outputs for toxicity, bias, empathy, and semantic alignment.
RLHF Optimization: Trains the model using composite human-centric rewards.
Deployment: Provides a real-time interface using Gradio and Hugging Face APIs.

🧠 **Core Features**
✅ Toxicity detection in English, Hindi, and Hinglish
✅ Emotionally intelligent rewriting of harmful content
✅ Custom evaluation metrics using empathy and semantic similarity
✅ Integrated RLHF feedback loop for fine-tuning outputs
✅ Secure, lightweight, and interactive web deployment

**🧪 Technologies Used**
Model Architectures
BERT, DistilBERT, XLM-RoBERTa (classification)
Sentence-BERT, Emotion-BERT (evaluation)
Granite 3.2-2B (LLM for paraphrasing)
Frameworks and Libraries
Hugging Face Transformers
Gradio
Python (3.8+)
PyTorch, NumPy, Pandas

📊 Model Performance
<img width="518" alt="image" src="https://github.com/user-attachments/assets/33f53ba5-5c3e-46fa-8d66-803f32f04da1" />

Metrics evaluated on multilingual toxic comment datasets with balanced splits.

📁 Datasets Used
Jigsaw Multilingual Toxic Comment Classification (Kaggle)
YouTube multilingual comment datasets
Manually annotated human feedback dataset for RLHF scoring

**⚙️ Getting Started**
📍 Live Demo: Launch the App on Hugging Face Spaces : https://janviml-toxic-comment-classifier.hf.space/

**📈 Evaluation Metrics**
Toxicity Score: Based on transformer classifier predictions

Empathy Score: Evaluated using fine-tuned Emotion-BERT

Bias Check: Flags implicit bias against groups

Semantic Similarity: Measures message preservation with Sentence-BERT

Reward Function: Custom RLHF metric combining all the above

**👥 Contributors**

Jahnavi Chintakindi – Project Lead, Classification Models, Integration
Poojitha Ganta – Prompt Engineering, Paraphrasing Pipeline
Ramya Rangaraju – RLHF Logic, Evaluation Metrics, Deployment

**🔮 Future Development**
🌐 Browser extension for Gmail, YouTube, and Twitter moderation
🔁 Continuous RLHF training loop via anonymous user feedback
📊 Public leaderboard with user-submitted toxic comment rewriters

**📄 License**
This project is licensed under the MIT License.

**Citation**
If you use this framework or our methodology in your research, please consider citing:

J. Chintakindi, P. Ganta, R. Rangaraju. ToxiFix: A Multilingual Emotion-Aware Toxic Comment Classification and Rewriting Framework, 2024.
https://github.com/JahnaviCh25/ToxicCommentClassificationUsingRLHF_Capstone


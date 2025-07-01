# azure-ai-900-prep-notes
📘 Study notes, key concepts, and learning resources for Microsoft Azure AI-900: Azure AI Fundamentals certification. Includes personal takeaways, visual breakdowns, and LinkedIn-ready materials.


🧠 AZURE AI FUNDAMENTALS – DETAILED STUDY NOTES
🔷 1. Azure AI Services – Overview
Azure AI Services is a collective term for Microsoft’s AI tools and platforms. It includes:

Azure Cognitive Services (pre-built AI)

Azure Machine Learning (build/train custom models)

Azure OpenAI Service (LLMs like GPT, DALL·E, Whisper)

Azure AI Studio (unified GenAI platform)

Azure Bot Service (Conversational AI)

🔷 2. Azure Cognitive Services – Categories & Details
A. 🔍 Vision
Pre-trained APIs to analyze visual content.

Service	Description	Use Cases
Computer Vision	Analyze images (objects, tags, description, OCR)	Detect labels, get alt-text
Custom Vision	Train your own image classifier	Classify damaged vs normal products
Face API	Detect faces, attributes (age, emotion)	Retail insights, security checks
Form Recognizer	Extract fields, tables from docs	Invoices, tax forms, IDs
Semantic Segmentation	Pixel-level classification of objects	Satellite imagery, medical scans
Domain Models	Celebrities, Landmarks	Media tagging, tourism apps

B. 🗣️ Speech
Convert between speech and text.

Service	Description	Use Cases
Speech to Text	Audio → Text	Meeting transcripts
Text to Speech	Text → Voice	Read out articles, IVR
Speech Translation	Live speech translation	Multilingual conferences
Speaker Recognition	Identify/verify speaker	Voice login, call centers

C. 🌐 Language
Natural Language Processing (NLP) services.

Service	Description	Use Cases
Text Analytics	Extract key phrases, sentiment, PII, entities	Analyze feedback, redact data
Translator (NMT)	Translate text in 90+ languages	Chatbots, web content
Language Understanding (LUIS)	Detect user intents/entities	Chatbots: "Book a flight"
Question Answering (ex-QnA Maker)	FAQ-style Q&A from documents	Self-service portals

D. 🤖 Decision
Services for intelligent recommendations and moderation.

Service	Description	Use Cases
Personalizer	Reinforcement learning-based personalization	News, product suggestions
Content Moderator	Detect offensive content in text/images	Social media platforms
Anomaly Detector	Detect time-series anomalies	Server monitoring, fraud detection

🔷 3. Azure Machine Learning – Detailed View
Used to build, train, and deploy custom ML models.

Component	Description	Keywords
Designer	Drag-drop UI for building ML pipelines	No code
AutoML	Auto-select algorithm + hyperparameters	Classification, regression
Notebooks	Jupyter-style coding for data scientists	Python
Datasets	Managed training data	Reusable
Compute Targets	CPU/GPU VMs for training	Scale up
Model Registry	Version control for ML models	Track performance
Endpoints	Deploy model as REST API	Real-time prediction
Pipelines	Automate end-to-end ML workflows	Production-ready

📌 ML Lifecycle:

Data → Preprocessing → Feature Engineering

Split into Train/Test

Train model → Evaluate (Accuracy, F1, AUC)

Deploy → Monitor

🔷 4. Machine Learning Concepts
Term	Definition	Examples
Supervised Learning	Input + known output	Classification, regression
Unsupervised Learning	No output labels	Clustering
Classification	Predict label/class	Email: spam/not spam
Regression	Predict numeric value	Price prediction
Clustering	Group similar items	Customer segmentation
PCA	Reduce features	Visualization
Ordinal Regression	Predict ranked categories	Ratings (1–5)
Poisson Regression	Predict counts	# of calls per day

🔷 5. Evaluation Metrics
Metric	Purpose	When to Use
Accuracy	Overall correctness	Balanced data
Precision	Correct Positives / All Positives	Reduce false positives
Recall	Correct Positives / All Actual Positives	Reduce false negatives
F1 Score	Harmonic mean of precision & recall	Imbalanced classes
AUC	Class separability	Binary classifiers

🔷 6. Responsible AI Principles
Principle	Description
Fairness	Prevent bias, ensure equity
Inclusiveness	Accessible to all users
Reliability & Safety	Work as intended in all scenarios
Transparency	Explain how decisions are made
Accountability	Human oversight and responsibility
Privacy & Security	Protect personal and sensitive data

🔷 7. Knowledge Mining
Combines OCR, Form Recognizer, Text Analytics, and Azure Cognitive Search

Used to turn unstructured documents into searchable knowledge

Common in legal, healthcare, finance

🔷 8. Conversational AI & Bot Service
Azure Bot Service + Cognitive Services

Tools:

Bot Framework SDK

LUIS for intent recognition

QnA for FAQ-style bots

Channels: Web Chat, MS Teams, Telegram, WhatsApp

🔷 9. Azure OpenAI & AI Studio (Modern AI)
Tool	Purpose
Azure AI Studio	Unified GUI for GenAI + prompt flow
Prompt Flow	LLM pipeline (prompt → completion)
Azure OpenAI Service	GPT-4, Codex, DALL·E, Whisper
Data Grounding	RAG – connect model to private data
Fine-Tuning	Customize LLMs with your data

🔷 10. Modern Naming Map (AI Studio)
Exam Term	Old Name	New Name
Vision Service	Computer Vision	Azure AI Vision – Image Analysis
OCR	Read API	Azure AI Vision OCR
Text Analytics	Text Analytics	Azure AI Content Understanding
Form Recognizer	Form Recognizer	Azure AI Document Intelligence
LUIS	Language Understanding	Conversational Language Understanding
QnA Maker	QnA Maker	Azure Language – Question Answering
Translator	Translator	Azure Language – Text Translation

🔷 11. Final Tips
Focus on use cases + keywords

Know which service fits which scenario

Practice drag-drop scenario questions

Understand end-to-end ML workflows

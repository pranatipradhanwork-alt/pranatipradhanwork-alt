# Hi, I'm Pranati 👋

AI/ML engineer who loves making small language models give big, trustworthy answers.
MCA graduate · open to AI/ML engineer roles anywhere in India.

## 🏦 Featured: HDFC Bank custom LLM pipeline

[Code](https://github.com/pranatipradhanwork-alt/Hdfc-bank-custom-llm-pipeline-project) ·
[Live app](https://shyam003-hdfc-ai-platform.hf.space) ·
[Demo video](https://drive.google.com/drive/folders/1rPJE1aa7948V_zUzESFsc6bPwTawB-9j?usp=sharing)

A governed pipeline that fine-tunes Llama 3.2 1B with LoRA / QLoRA, answers bank FAQs from
retrieved sources with citations, and only releases a model after evaluation, red-team tests and approval.

- **Found and fixed the main failure:** human review showed the model went wrong when customers
  reworded questions. Training it on the same prompt it is served with raised customer-worded
  ROUGE-L from 0.51 to 0.91 and fully correct answers from 62% to 82%.
- **Led the fine-tuning pipeline:** one training script for NVIDIA GPUs (QLoRA), Apple Silicon and CPU,
  every run tracked in MLflow.
- **Safety and release:** input and output guardrails, a 36-case red-team suite, a model registry
  with approvals, checksums and one-click rollback.

## 🌱 Other projects

- [Tata Steel machine failure prediction](https://github.com/pranatipradhanwork-alt/Tata_Steel_machine_failure_predict):
  classification on imbalanced data (1.57% failures), Random Forest with threshold tuning, Streamlit demo.
- [LMS](https://github.com/pranatipradhanwork-alt/lms): my MCA project, a full-stack course marketplace
  with Stripe payments and payouts, video lessons on AWS S3 and progress tracking (Next.js, Express, MongoDB).

## 🧰 Skills

**GenAI and ML:** LLM fine-tuning (LoRA, QLoRA), RAG, embeddings, LLM evaluation, guardrails, scikit-learn  
**Libraries:** PyTorch · Hugging Face Transformers, PEFT, TRL · sentence-transformers · pandas · NumPy  
**Engineering:** Python · SQL · FastAPI · MLflow · Docker · Git · React · Node.js · MongoDB  
**Data and BI:** SQL · pandas · Excel · Power BI · Tableau

## 📫 Say hi

[LinkedIn](https://www.linkedin.com/in/pranati-pradhan-7766b31a7)

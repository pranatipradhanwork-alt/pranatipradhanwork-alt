# Hi, I'm Pranati 👋

AI/ML engineer who loves making small language models give big, trustworthy answers.
MCA graduate · open to AI/ML engineer roles anywhere in India.

## 🧰 Skills

![LoRA / QLoRA](https://img.shields.io/badge/LoRA_%2F_QLoRA-7B3FE4?style=for-the-badge) ![RAG](https://img.shields.io/badge/RAG-0F766E?style=for-the-badge) ![LLM evaluation](https://img.shields.io/badge/LLM_evaluation-B45309?style=for-the-badge) ![Guardrails](https://img.shields.io/badge/Guardrails-B91C1C?style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)  
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)  
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge) ![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge)

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

## 📫 Say hi

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/pranati-pradhan-7766b31a7)

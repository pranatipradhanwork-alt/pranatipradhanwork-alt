# Hi, I'm Pranati 👋

Aspiring AI/ML engineer who loves making small language models give big, trustworthy answers.
MCA graduate · M.Sc. in AI & ML (Woolf University, AlmaBetter) in progress · open to GenAI / AI/ML engineer roles anywhere in India.

## 🧰 Skills

![LoRA / QLoRA](https://img.shields.io/badge/LoRA_%2F_QLoRA-7B3FE4?style=for-the-badge) ![RAG](https://img.shields.io/badge/RAG-0F766E?style=for-the-badge) ![LLM evaluation](https://img.shields.io/badge/LLM_evaluation-B45309?style=for-the-badge) ![Guardrails](https://img.shields.io/badge/Guardrails-B91C1C?style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)  
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)  
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

- [Voyage Analytics: travel MLOps platform](https://github.com/pranatipradhanwork-alt/travel-mlops):
  flight price regression (R² 0.88 on unseen routes), gender classifier (89.4%) and hotel recommender,
  served by a Flask API on Kubernetes (autoscaling 2 to 10 pods) with Airflow retraining, Jenkins CI/CD and MLflow.
- [Tata Steel machine failure prediction](https://github.com/pranatipradhanwork-alt/Tata_Steel_machine_failure_predict):
  classification on imbalanced data (1.57% failures), Random Forest with threshold tuning, Streamlit demo.
- [Amazon Prime Video TV shows and movies EDA](https://github.com/pranatipradhanwork-alt/amazon_tvshows_movies_EDA):
  pandas and NumPy analysis of 9,871 titles and 124,235 credits; catalog is 86% movies, releases jump after 2015,
  and neither runtime nor age rating predicts IMDb score.
- [LinkedIn product dissection](https://github.com/pranatipradhanwork-alt/linkedin-product-dissection):
  how LinkedIn solves four professional problems, plus a 9-table MySQL schema and ER diagram.
- [LMS](https://github.com/pranatipradhanwork-alt/lms): my MCA project, a full-stack course marketplace
  with Stripe payments and payouts, video lessons on AWS S3 and progress tracking (Next.js, Express, MongoDB).

## 📫 Say hi

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white)](https://www.linkedin.com/in/pranati-pradhan)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pranatipradhanwork@gmail.com)
[![HackerRank](https://img.shields.io/badge/HackerRank-Python_%26_SQL_silver-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/pranatipradhanw1)

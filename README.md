# 🎯 Python Requirements Collection

> **A comprehensive, production-ready collection of `requirements.txt` files for Data Science, ML, AI, and Engineering projects**

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintained: Yes](https://img.shields.io/badge/Maintained-Yes-green.svg)](https://github.com/)

---

## 📚 What's Inside?

This repository contains **battle-tested, production-grade requirements files** for various data and AI domains. Each file is carefully curated with:

✅ **Pinned versions** for reproducibility  
✅ **Python 3.10+ compatibility**  
✅ **Industry-standard packages**  
✅ **Comprehensive comments** explaining each package  
✅ **Both full-featured and simplified versions**

---

## 🗂️ Repository Structure

```
requirements/
│
├── 📊 Data Analytics
│   ├── requirements_da.txt          # Full-featured analytics stack
│   └── simple-da.txt                # Lightweight version
│
├── ⚙️ Data Engineering
│   ├── requirements-de.txt          # Complete DE toolkit
│   └── simple-de.txt                # Basic ETL essentials
│
├── 🔬 Data Science
│   ├── requirements-ds.txt          # Advanced statistical analysis
│   └── simple-ds.txt                # Core DS packages
│
├── 🤖 Machine Learning
│   ├── requirements-ml.txt          # Classical ML & AutoML
│   └── requirements-all-ml.txt      # All ML categories
│
├── 🧠 Deep Learning
│   └── requirements-dl.txt          # PyTorch, TF, Vision, NLP
│
└── 🚀 AI Agents / LLM
    └── requirements-ai-llm.txt      # LangChain, RAG, Agents
```

---

## 🎯 Quick Start

### 1️⃣ Choose Your Domain

Pick the requirements file that matches your project:

| Domain | File | Use Case |
|--------|------|----------|
| 📊 **Data Analytics** | `requirements_da.txt` | BI, reporting, dashboards, EDA |
| 📊 **Simple Analytics** | `simple-da.txt` | Basic pandas analysis, quick prototypes |
| ⚙️ **Data Engineering** | `requirements-de.txt` | ETL pipelines, Airflow, PySpark, cloud |
| ⚙️ **Simple DE** | `simple-de.txt` | Basic data pipelines, database ops |
| 🔬 **Data Science** | `requirements-ds.txt` | Statistical analysis, experimentation |
| 🔬 **Simple DS** | `simple-ds.txt` | Core ML, hypothesis testing, forecasting |
| 🤖 **Machine Learning** | `requirements-ml.txt` | Classical ML, AutoML, model deployment |
| 🧠 **Deep Learning** | `requirements-dl.txt` | PyTorch, TF, CV, NLP, RL |
| 🚀 **AI/LLM** | `requirements-ai-llm.txt` | LangChain, RAG, vector DBs, agents |
| 🎓 **All ML Categories** | `requirements-all-ml.txt` | Supervised, unsupervised, RL |

### 2️⃣ Install Dependencies

```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install from your chosen requirements file
pip install -r requirements-ml.txt
```

### 3️⃣ Start Building! 🚀

---

## 🔍 Detailed Breakdowns

### 📊 Data Analytics Stack

**Full Version** (`requirements_da.txt`):
- **Data Manipulation**: pandas, numpy, polars
- **Visualization**: matplotlib, seaborn, plotly, dash, bokeh, altair
- **BI Tools**: great-expectations, sweetviz, pandas-profiling
- **Database**: SQLAlchemy + drivers (PostgreSQL, MySQL, Oracle)
- **Statistics**: scipy, statsmodels, pingouin
- **Time Series**: prophet, pmdarima
- **Jupyter**: Full notebook ecosystem

**Simple Version** (`simple-da.txt`):
- Core: pandas, numpy, matplotlib, seaborn, plotly
- Database: SQLAlchemy + PostgreSQL
- Perfect for quick analysis and prototypes

---

### ⚙️ Data Engineering Stack

**Full Version** (`requirements-de.txt`):
- **Orchestration**: Airflow (AWS/GCP), Prefect, Dagster
- **Big Data**: PySpark, Delta Lake, Dask
- **Databases**: PostgreSQL, MySQL, MongoDB, Redis, Cassandra, ClickHouse, Snowflake
- **Cloud**: AWS (boto3), GCP (BigQuery, Storage), Azure
- **Streaming**: Kafka, RabbitMQ
- **API**: FastAPI, Uvicorn

**Simple Version** (`simple-de.txt`):
- Core: pandas, Prefect, FastAPI
- Cloud: AWS boto3, GCP Storage
- Databases: PostgreSQL, MySQL, MongoDB

---

### 🔬 Data Science Stack

**Full Version** (`requirements-ds.txt`):
- **Scientific**: NumPy, SciPy, SymPy, Numba
- **Statistics**: statsmodels, pingouin, lifelines
- **ML**: scikit-learn, XGBoost, LightGBM, CatBoost
- **Time Series**: prophet, pmdarima, sktime, tsfresh
- **Causal Inference**: DoWhy, CausalML
- **Bayesian**: PyMC, ArviZ
- **NLP**: NLTK, spaCy, Gensim
- **CV**: OpenCV, scikit-image
- **Explainability**: SHAP, LIME, InterpretML

**Simple Version** (`simple-ds.txt`):
- Core DS tools for analysis, modeling, and interpretation
- Perfect for academic projects and learning

---

### 🤖 Machine Learning Stack

**Full Version** (`requirements-ml.txt`):
- **Core ML**: scikit-learn, XGBoost, LightGBM, CatBoost
- **Feature Engineering**: featuretools, category-encoders
- **HPO**: Optuna, Hyperopt, Ray Tune
- **AutoML**: auto-sklearn, TPOT, PyCaret, H2O
- **Explainability**: SHAP, LIME, InterpretML, Alibi
- **MLOps**: MLflow, BentoML, Evidently
- **Experiment Tracking**: Weights & Biases, Neptune, Comet ML

---

### 🧠 Deep Learning Stack

**Full Version** (`requirements-dl.txt`):
- **Frameworks**: PyTorch, TensorFlow, Keras, Lightning
- **Vision**: timm, Detectron2, MMDetection, YOLOv5, Albumentations
- **NLP**: transformers, PEFT (LoRA), Accelerate
- **GNN**: PyTorch Geometric, DGL
- **RL**: Stable-Baselines3, Ray RLlib
- **Audio**: librosa, SpeechBrain
- **Distributed**: Horovod, DeepSpeed
- **Serving**: TorchServe, Triton, BentoML

---

### 🚀 AI Agents / LLM Stack

**Full Version** (`requirements-ai-llm.txt`):
- **Frameworks**: LangChain, LlamaIndex, Semantic Kernel, Haystack
- **LLM APIs**: OpenAI, Anthropic, Cohere, Gemini, Groq
- **Local Inference**: vLLM, llama-cpp-python, ExLLaMA
- **Vector DBs**: ChromaDB, FAISS, Pinecone, Weaviate, Qdrant
- **Embeddings**: sentence-transformers, OpenAI
- **Agents**: AutoGen, CrewAI, LangGraph
- **RAG**: Document processing (PDF, DOCX, PPTX), RAGAS
- **Safety**: Guardrails AI, Presidio (PII detection)
- **Observability**: LangSmith, Phoenix, Langfuse
- **Serving**: Gradio, Streamlit, Chainlit, LiteLLM

---

### 🎓 All ML Categories Stack

**Full Version** (`requirements-all-ml.txt`):
- **Supervised**: XGBoost, LightGBM, PyTorch, TensorFlow, Prophet
- **Unsupervised**: HDBSCAN, UMAP, PyOD, BERTopic
- **Reinforcement**: Stable-Baselines3, Ray RLlib, Gym
- **Semi-supervised**: CleanLab
- **Transfer Learning**: timm, transformers
- **Active Learning**: modAL
- **Online Learning**: River

---

## 💡 Best Practices

### Version Management
```bash
# Create a requirements file from your current environment
pip freeze > requirements.txt

# Install specific versions
pip install -r requirements-ml.txt

# Upgrade packages (be careful!)
pip install --upgrade -r requirements-ml.txt
```

### Virtual Environments
Always use virtual environments to avoid dependency conflicts:

```bash
# Using venv
python -m venv myproject_env
source myproject_env/bin/activate

# Using conda
conda create -n myproject python=3.10
conda activate myproject
```

### Docker Integration
```dockerfile
FROM python:3.10-slim

WORKDIR /app
COPY requirements-ml.txt .
RUN pip install --no-cache-dir -r requirements-ml.txt

COPY . .
CMD ["python", "main.py"]
```

---

## 🔄 Keeping Dependencies Updated

```bash
# Check for outdated packages
pip list --outdated

# Use pip-audit for security vulnerabilities
pip install pip-audit
pip-audit

# Use safety for security checks
pip install safety
safety check
```

---

## 🤝 Contributing

Found a package that should be included? Have suggestions? Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Add your improvements
4. Submit a pull request

---

## 📖 Package Explanations

Each requirements file includes detailed comments explaining:
- What each package does
- Why it's included
- Common use cases
- Dependencies and compatibility notes

---

## ⚠️ Important Notes

- **Python Version**: All requirements are tested with Python 3.10+
- **Compatibility**: Some packages may have OS-specific dependencies
- **GPU Support**: Deep learning packages may require CUDA for GPU acceleration
- **Cloud Credentials**: Cloud SDK packages require proper authentication setup
- **API Keys**: LLM packages require API keys from respective providers

---

## 🏆 Why Use These Requirements?

✨ **Curated**: Only industry-standard, production-ready packages  
✨ **Tested**: All versions are verified for compatibility  
✨ **Documented**: Clear explanations for each package  
✨ **Flexible**: Both comprehensive and minimal versions  
✨ **Updated**: Regular maintenance and updates  

---

## 📞 Support

- 📧 Questions? Open an issue
- 💬 Discussions? Start a discussion thread
- 🐛 Found a bug? Report it in issues
- ⭐ Like this repo? Give it a star!

---

## 📄 License

MIT License - feel free to use in your projects!

---

## 🙏 Acknowledgments

Built with ❤️ for the data science and AI community.

Special thanks to all the amazing open-source contributors whose packages make our work possible!

---

<div align="center">

**Happy Coding! 🚀**

If this helped you, consider giving it a ⭐!

</div>

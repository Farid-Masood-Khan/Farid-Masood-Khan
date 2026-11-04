# Hi, I'm Farid Masood Khan 👋

**Applied Machine Learning & MLOps Engineer**  
Specializing in production ML pipelines, low-latency edge inference, hybrid enterprise RAG, and uncertainty-calibrated time series forecasting.

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-3776AB?logo=python&logoColor=white)](https://python.org)
[![MLOps](https://img.shields.io/badge/MLOps-DVC%20%7C%20Feast%20%7C%20MLflow-017CEE)](https://github.com/Farid-Masood-Khan/mlforge-mlops)
[![Testing](https://img.shields.io/badge/Test%20Suite-91%20Tests%20Passing-success)](https://github.com/Farid-Masood-Khan)
[![Architecture](https://img.shields.io/badge/Engineering-Production--Grade-blueviolet)](https://github.com/Farid-Masood-Khan)
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

---

## 🎯 Engineering Philosophy

> **No "vibe-coded" scripts or throwaway notebooks.** Every system I build enforces deterministic pipelines, strict schema validation, out-of-distribution gates, calibrated confidence scores, and automated test coverage before reaching production.

- **Data Integrity First**: Time-aware and entity-isolated splitting to prevent target and group leakage.
- **Uncertainty Calibration**: Models report honest probability distributions (ECE temperature scaling and empirical prediction intervals), not raw overconfident logits.
- **Production Guardrails**: Automated drift detection (KS & PSI tests), schema checks (Great Expectations), and edge quality filtering (Laplacian blur gates).
- **Clean Software Architecture**: Modular packaging, type safety, FastAPI microservices, containerization, and reproducibility via DVC and MLflow.

---

## 🚀 Featured Production Repositories

| Repository | Domain | Core Tech Stack | Production Highlights | Tests |
| :--- | :--- | :--- | :--- | :---: |
| [**`mlforge-mlops`**](https://github.com/Farid-Masood-Khan/mlforge-mlops) | Credit Risk MLOps Continuous Delivery | Feast, MLflow, DVC, LightGBM, Great Expectations, FastAPI | DVC multi-stage pipeline, point-in-time correct Feast store, KS & PSI distribution drift monitoring, automated Champion/Challenger registry. | **26 / 26** ✅ |
| [**`documind-rag`**](https://github.com/Farid-Masood-Khan/documind-rag) | Enterprise Document Retrieval (RAG) | FastAPI, Streamlit, BM25 Okapi, BAAI Cross-Encoder, SQLModel | Sentence-window chunking, hybrid dense + lexical retrieval, Reciprocal Rank Fusion (RRF), cross-encoder re-ranking, and grounded citation verification. | **12 / 12** ✅ |
| [**`cropguard-agri-ai`**](https://github.com/Farid-Masood-Khan/cropguard-agri-ai) | Edge Computer Vision & Agriculture AI | PyTorch, MobileNetV3-Small, ONNX Runtime, FastAPI | Quantized ONNX engine (16.1 MB, 2.1 ms latency), Platt/temperature scaling ECE calibration (0.0257), and pre-inference Laplacian blur rejection gate. | **17 / 17** ✅ |
| [**`urdunlp-toolkit`**](https://github.com/Farid-Masood-Khan/urdunlp-toolkit) | Low-Resource & Roman Urdu NLP | Scikit-Learn, Regex Engine, Streamlit, Pytest | Rule-based unicode normalizer (-15.26% vocabulary reduction), Jaccard anti-leakage splitting, and calibrated tri-class sentiment classification. | **18 / 18** ✅ |
| [**`trendcast-forecasting`**](https://github.com/Farid-Masood-Khan/trendcast-forecasting) | Time-Series Economic Forecasting | Statsmodels, Prophet, Plotly, Streamlit | Real WFP Pakistan commodity market series (2004–2026), expanding-window rolling backtesting, calibrated residual intervals (81.8% PICP), baseline gates. | **18 / 18** ✅ |
| [**`Frugal-ML-Extension`**](https://github.com/Farid-Masood-Khan/Frugal-ML-Extension) | Food Waste Reduction & Retail AI | Python, Machine Learning, Streamlit, FastAPI | Intelligent grocery inventory demand forecasting and shelf-life spoilage classification microservice for sustainable retail. | Verified |

---

## 🛠️ Technical Stack & Tooling

```
MLOps & Infrastructure ── Feast Feature Store · MLflow · DVC · Docker · Great Expectations · GitHub Actions
Machine Learning       ── Scikit-Learn · LightGBM · XGBoost · Statsmodels · Prophet · PyTorch
Computer Vision        ── MobileNetV3 · ONNX Runtime Quantization · OpenCV · Image Quality Triage
NLP & Information Ret. ── Sentence Transformers · BM25 Okapi · Cross-Encoder Reranking · Text Normalization
Backend & APIs         ── FastAPI · Pydantic v2 · SQLModel · SQLite · Streamlit · RESTful microservices
Testing & Reliability  ── Pytest · Mypy · Ruff · KS-Testing · Population Stability Index (PSI)
```

---

## 📊 Portfolio Test & Quality Metrics

All five portfolio systems are fully tested, self-contained, and reproducible:
- **91 Total Unit & Integration Tests** passing with zero warnings.
- **Strict Seed Control** (`42`) across all stochastic splits and model initializations.
- **Zero Raw Notebooks in Production**: Every pipeline runs via tested Python packages and CLI/REST endpoints.

---

## 📬 Contact & Collaboration

- **Email**: [faridmasoodofficial@gmail.com](mailto:faridmasoodofficial@gmail.com)
- **GitHub**: [@Farid-Masood-Khan](https://github.com/Farid-Masood-Khan)
- **Open for**: Applied ML Engineer, MLOps Engineer, and Machine Learning Systems roles.

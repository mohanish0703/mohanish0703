## Hi, I'm Mohanish Gupta

Computer Science student at **VIT Vellore** (B.Tech CSE, 2027) looking for **Data Analyst and Data Scientist** roles.
I work across the whole path from raw data to a decision: SQL and Power BI for analysis and reporting,
Python, scikit-learn and PyTorch for modelling, and LLM agents where judgment calls need to scale.
I report results against a baseline, including when the model barely beats it.

- **Now:** final-year capstone on intrusion detectors that keep learning after deployment without being poisoned
- **Previously:** ML Intern at **C-DAC Pune** (Jun–Jul 2026), predicting remaining useful life of turbofan engines and batteries with PyTorch
- **Contact:** mohanish.0703@gmail.com

### Tech stack

| Area | Skills |
|---|---|
| Languages | Python, SQL (MySQL, PostgreSQL), C++, TypeScript |
| Machine Learning | Regression & Classification, Time-Series Forecasting, Feature Engineering, Cross-Validation (GroupKFold), Hyperparameter Tuning, Model Calibration, Conformal Prediction, SHAP |
| Deep Learning & LLMs | PyTorch, Transformers, LSTMs/RNNs, LangGraph, Gemini, Agentic AI |
| Data Analysis & Statistics | Exploratory Data Analysis, Data Cleaning & Preprocessing, Statistical Analysis, Hypothesis Testing, Data Visualization |
| Analytics & BI | Power BI, Excel |
| MLOps & Tools | FastAPI, Docker, MLflow, GitHub Actions, Azure, Streamlit, Next.js, SQLite, Git, Jupyter, VS Code |
| Libraries | Pandas, NumPy, Scikit-learn, XGBoost, River, Pydantic, Matplotlib, Seaborn |

### Featured projects

| Project | What it does | Built with |
|---|---|---|
| [**ShortlistAI**](https://github.com/mohanish0703/shortlist-ai) | A LangGraph agent that ranks resumes for high-volume jobs, gives each candidate a reason that cites the resume, and waits for a recruiter to approve. **95.5%** field-extraction accuracy on 150 synthetic resumes in five messy formats (including Hinglish); on 50 hand-labelled resumes, precision@5 of **0.76** vs 0.62 for a random order and 0.64 for BM25. | LangGraph, Gemini, FastAPI, Streamlit, SQLite |
| [**Trust-Aware IDS**](https://github.com/mohanish0703/trust-ids-poc) *(team capstone)* | An authorization gate that decides whether a continually-learning IoT intrusion detector may update, using a reputation signal independent of the traffic. On 6 unseen N-BaIoT devices it accepted **0 of 1,620** poisoned updates, against 383 for a traffic-only gate. The reputation signal is simulated. | Python, River, Streamlit, D3.js |
| [**Credit Risk Analysis**](https://github.com/mohanish0703/credit-risk-analysis) | Default risk on **779K** LendingClub loans: SQL analysis by grade, income, DTI and FICO, then XGBoost on a time-based split. It edges out LendingClub's own sub-grade (ROC-AUC **0.691** vs 0.682), and a profit-maximising approval cutoff added no gain. Power BI dashboard on top. | PostgreSQL, XGBoost, SHAP, Power BI |
| [**Turbofan RUL**](https://github.com/mohanish0703/turbofan-rul) *(in progress)* | Predicts how many cycles a jet engine has left, on NASA's C-MAPSS data. Engine-grouped cross-validation so no engine leaks between train and test; current XGBoost baseline reaches **13.35 RMSE** on the FD001 test set. | Python, scikit-learn, XGBoost |
| [**Bank Loan Analysis**](https://github.com/mohanish0703/Bank-Loan-Analysis) | Dashboard over ~38,000 loans: good vs. bad loans, funded and received amounts, and trends by month, state, purpose and term. | MySQL, Power BI |
| [**Document Summary Assistant**](https://github.com/mohanish0703/Document-Summary-Assistant) | Upload a PDF or image and get a short, medium or long summary, with OCR for scanned pages. [Live demo](https://document-summary-assistant-xi-eight.vercel.app/) | Next.js, TypeScript |
| [**Pizza Sales Report**](https://github.com/mohanish0703/Pizza-Sales-Report) | Sales KPIs, daily and monthly trends, and best and worst sellers, with every Power BI figure checked against SQL. | SQL, Power BI |
| [**CineMatch**](https://github.com/mohanish0703/Movie-Recommendation) | Content-based movie recommender over 5,000 TMDB titles using cosine similarity, served as a Streamlit app. | Python, scikit-learn, Streamlit |
| [**Student Performance Predictor**](https://github.com/mohanish0703/Student-Perfomance-Predictor) | Predicts exam scores from demographic and study factors, from EDA through model comparison. | Python, scikit-learn |

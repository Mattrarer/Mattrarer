## Hi, I'm Mateo Aranguren 👋

Data scientist and statistician working on **electoral data** in Colombia. I build statistical and machine-learning pipelines for public data: survey and audit sampling, anomaly detection, forecasting and recommender systems. I care about validation as much as models: temporal hold-outs, leakage control, honest baselines.

- 🏛️ Professional at Colombia's National Electoral Council (CNE): electoral data analysis and oversight of electoral technology
- 🎓 MSc candidate in Statistics and Data Science
- 🛠️ Python · R · SQL/DuckDB · scikit-learn · TensorFlow/Keras · PyTorch · pandas · sf · Shiny
- 🌎 Spanish (native) · English

> 🇪🇸 *Científico de datos y estadístico enfocado en datos electorales. Trabajo con muestreo, detección de anomalías, pronóstico y sistemas de recomendación.*

---

### ⭐ Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**election-anomaly-detection**](https://github.com/Mattrarer/election-anomaly-detection) | Tested Python package for election forensics: Benford/last-digit tests, a size-preserving Monte Carlo null and within-county robust outliers, on 10k+ Pennsylvania 2020 precincts | Python, SciPy, pytest, CI |
| [**hm-hybrid-recommender**](https://github.com/Mattrarer/hm-hybrid-recommender) | Hybrid recommender on 31.8M H&M transactions: stratified sampling, 5 clustering methods, 8 recommenders, rank fusion, temporal validation, bootstrap CIs | Python, DuckDB, scikit-learn |
| [**predictive-maintenance-ai4i**](https://github.com/Mattrarer/predictive-maintenance-ai4i) | Unsupervised maintenance "traffic light": flags 4.3 % of machines that hold 30 % of failures, without using failure labels (group project) | scikit-learn, DBSCAN, PCA |
| [**bitcoin-forecasting-deep-learning**](https://github.com/Mattrarer/bitcoin-forecasting-deep-learning) | LSTM, GRU, BiLSTM, CNN-LSTM and Transformer vs. naive forecast; the LSTM cuts RMSE by 75 % | TensorFlow/Keras |
| [**sms-spam-detection-rnn**](https://github.com/Mattrarer/sms-spam-detection-rnn) | RNN/LSTM/GRU spam filter with class weighting and Keras Tuner: F1 0.958, zero false positives on test | Keras, Keras Tuner |
| [**eigenfaces-face-recognition**](https://github.com/Mattrarer/eigenfaces-face-recognition) | SVD eigenfaces + 5 classifiers with leakage-free CV and 10-seed robustness checks | NumPy, SciPy, scikit-learn |
| [**music-recommender-lastfm**](https://github.com/Mattrarer/music-recommender-lastfm) | Four recommenders on Last.fm and why RMSE misleads for top-N recommendation | pandas, SVD, Apriori |
| [**gender-gaps-shiny-dashboard**](https://github.com/Mattrarer/gender-gaps-shiny-dashboard) | Interactive R dashboard on education, women's labour participation and poverty (Gapminder) | R, Shiny, flexdashboard |

---

### 🔍 How I work

- **Baselines first**: every model is compared with a naive or popularity baseline.
- **Validation that matches reality**: temporal splits for time-dependent data, and test sets used once.
- **Uncertainty, not only point estimates**: bootstrap intervals, multiple seeds, simulation-based nulls.
- **Reproducible**: `requirements.txt`, public data sources and no credentials in code.

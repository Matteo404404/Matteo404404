<div align="center">

# Matteo Melis

**Data Science · Quantitative Finance · AI**

[![Email](https://img.shields.io/badge/matteomelis04%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:matteomelis04@gmail.com)
[![Location](https://img.shields.io/badge/📍_Eindhoven,_NL-333333?style=flat-square)]()
[![TU/e](https://img.shields.io/badge/TU_Eindhoven-BSc_Data_Science-0066CC?style=flat-square)]()

</div>

---

BSc Data Science @ TU Eindhoven (2024–present) · English & Italian.

I build research-grade ML systems across quantitative finance, reinforcement learning, and computational social science. Projects are designed to be real — real data, validated methods, honest benchmarks, reproducible on a laptop. Alongside university I work as a Data Scientist at [TS Homesharing](https://github.com/TSHomesharing), building Azure-based automation, BI pipelines and Machine learning algorithms and agents in production.

---

## Projects

<table>
<tr>
<td width="50%">

### [Optiver-Realized-Volatility-Research-Pipeline](https://github.com/Matteo404404/Optiver-Realized-Volatility-Research-Pipeline)
**GNN + LightGBM volatility prediction**

End-to-end pipeline on Optiver LOB data. GraphSAGE on dynamic 112-stock correlation graphs (RMSPE 0.294), LightGBM with time-ID K=50 nearest-neighbour features replicating the Kaggle #1 trick (0.278), optimal ensemble blend, and Ridge stacking meta-learner reaching **RMSPE 0.220 / R² 0.886**. Includes a full systemic risk simulation layer: Eisenberg-Noe clearing, DebtRank, PENN model for topology generalization, and a Streamlit dashboard.

`PyTorch` `PyG` `LightGBM` `NetworkX` `Streamlit`

</td>
<td width="50%">

### [deep-rl-market-maker-lob](https://github.com/Matteo404404/deep-rl-market-maker-lob)
**Deep RL market making on a synthetic LOB**

Gymnasium-compatible LOB simulator with inventory and adverse selection penalties. DQN agent (SB3) vs Avellaneda–Stoikov analytical baseline. DQN without vol features achieves **Sharpe 1.95 / Sortino 3.13** vs AS Sharpe 0.10. Stochastic vol regime experiments (low/mid/high σ). Streamlit dashboard for PnL, Sharpe/Sortino, inventory risk.

`PyTorch` `Stable-Baselines3` `Gymnasium` `Streamlit`

</td>
</tr>
<tr>
<td width="50%">

### [reddit-polarization-lab](https://github.com/Matteo404404/reddit-polarization-lab)
**Network-based political polarization analysis**

Social network analysis lab on 12.67M Reddit submissions and 85.9M user relations. Structural polarization metrics: assortativity r = 0.759, echo index = 0.881, Louvain modularity = 0.736, mean community purity = 99.3%. Counterfactual rewiring experiments reveal **de-polarization requires 3.6× more structural effort than equivalent re-polarization**. Bounded-confidence opinion dynamics on the real graph.

`NetworkX` `python-louvain` `pandas` `scikit-learn` `matplotlib`

</td>
<td width="50%">

### [smart-hvac-rl-lab](https://github.com/Matteo404404/smart-hvac-rl-lab)
**RL for building energy control**

SAC and PPO agents controlling a single-zone building modelled as a 1-node RC thermal circuit (exact ZOH discretisation). Hysteresis thermostat and PID baselines. Full Gymnasium environment, training scripts, policy analysis notebooks, and pytest suite. Possible extensions: multi-zone, time-of-use tariffs, CO₂ cost terms.

`Stable-Baselines3` `Gymnasium` `SciPy` `NumPy` `Matplotlib`

</td>
</tr>
<tr>
<td width="50%">

### [econlab-causal-macro-rl](https://github.com/Matteo404404/econlab-causal-macro-rl)
**Causal macro-finance simulator with a learning central bank**

Structural causal model (SCM) macro environment with a Taylor-rule baseline and a Gymnasium-compatible central bank agent. Minimal macro state transition system, smoke tests, and a clean extensible design for studying policy interventions under uncertainty.

`Gymnasium` `statsmodels` `pandas` `Python`

</td>
<td width="50%">

### [AI_pertrophy](https://github.com/Matteo404404/AI_pertrophy)
**Evidence-based hypertrophy training app**

Desktop app with a hybrid LSTM / Banister fitness-fatigue predictor (routes to LSTM when enough user data exists), RAG chatbot via local Ollama (`qwen3:1.7b`), USDA FoodData Central nutrition lookup, SRA analytics, 1RM trends, and a 3-tier knowledge assessment gate. 76 exercises with biomechanical metadata. Full PyQt6 GUI, SQLite backend (15+ tables).

`PyTorch` `PyQt6` `SQLite` `Ollama` `REST APIs`

</td>
</tr>
</table>

---

## Work

**Data Scientist @ [TS Homesharing]** *(current)*
Building Python automation pipelines, Azure Functions, BI tooling, smart agents for automations in production for a homesharing platform. 

---

## Skills

| Domain | Stack |
|---|---|
| **Languages** | Python · R · Java · SQL · LaTeX |
| **ML / DL** | PyTorch · TensorFlow · scikit-learn · LightGBM · XGBoost · PyTorch Geometric |
| **Reinforcement Learning** | Stable-Baselines3 · Gymnasium · PPO · SAC · DQN |
| **Network Analysis** | NetworkX · python-louvain · PyG · graph centrality · GNNs |
| **Quant / Econometrics** | statsmodels · Bayesian inference · time series · stochastic processes · Eisenberg-Noe · DebtRank |
| **Data Engineering** | pandas · NumPy · SciPy · Polars · Parquet · SQLite · PostgreSQL |
| **Cloud / Infra** | Azure Functions · Docker · REST APIs · Git · Linux (Arch) |
| **Visualization** | Matplotlib · Seaborn · Plotly · Streamlit · PyQt6 |

---

<div align="center">
<sub>📫 matteomelis04@gmail.com</sub>
</div>

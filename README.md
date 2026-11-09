# Antoine Gilson

Statistics & Machine Learning graduate — [École Polytechnique](https://www.polytechnique.edu) (M2 Data Science) and [ENSAE Paris](https://www.ensae.fr/en).

I work on deep learning for physical and scientific data, and on the statistical evaluation of ML models — in particular, on when a reported improvement can actually be trusted.

Currently looking for a **PhD position** or a research-oriented role.

[LinkedIn](https://www.linkedin.com/in/antoine-gilson/) · `antoine[dot]gilson[at]polytechnique[dot]edu` · `antoine[dot]gilson[at]icloud[dot]com`

---

## Experience

- **Thales R&D** — Moirans, France (2026)
  Deep learning scatter correction for dual-layer spectral cone-beam CT, with physics-informed architectures.
- **Okinawa Institute of Science and Technology** — Japan (2025)
  Benchmark of foundation models and non-contrastive representation learning; fine-tuning of PhiNet v2 on temporal visual sequences.
- **Royal Belgian Football Association** — Tubize, Belgium (2025)
  Tracking data: multi-agent trajectory modelling on set pieces and statistical performance metrics for tactical analysis.
- **Paris Brain Institute, ARAMIS Lab** — Paris, France (2024)
  Performance uncertainty and statistical validity of model comparisons in medical imaging AI. Two co-authored papers (below).

## Publications

- P. André et al. — *Performance uncertainty in medical image analysis: a large-scale investigation of confidence intervals.* [arXiv:2601.17103](https://arxiv.org/abs/2601.17103), 2026.
- E. Christodoulou et al. — *False Promises in Medical Imaging AI? Assessing Validity of Outperformance Claims.* [arXiv:2505.04720](https://arxiv.org/abs/2505.04720), 2025.

---

## Selected projects

### Machine learning research projects

- **Low-rank optimal transport with latent coupling (FRLC) in OTT-JAX** — Implementation of FRLC (Halmos et al., NeurIPS 2024) on top of OTT-JAX, compared with the toolbox's low-rank Sinkhorn solver. Optimal Transport course of Marco Cuturi (ENSAE).
  [Repo](https://github.com/AntoineGilsonGH/Low-Rank-OT-FRLC-OTT-JAX)
- **Robust federated learning via spectral methods** — PCA-based detection of malicious gradients, with theoretical guarantees in a Gaussian mixture model (population and finite-sample regimes); implemented with power iteration and benchmarked against robust aggregators under gradient-poisoning attacks. École Polytechnique. *With C. Gadeau, M. Coppa and M. Simoneau.*
  [Repo](https://github.com/AntoineGilsonGH/Federated-Learning-Research)
- **Time-series foundation models for classification** — Adapting pretrained Moirai encoder representations to multivariate classification on LSST (pooling strategies, patch scales, LoRA): 0.66 accuracy, on par with classical ML baselines and +0.06 over a CNN. Supervised by R. Tavenard. *With M. Coppa, M. Simoneau and A. Vautrin.*
  [Repo](https://github.com/Alpharama/DLforTimeSeries)
- **Molecular graph captioning** — Graph-to-text retrieval: GNN encoders (GCN, GINE, GAT) aligned contrastively with pretrained text encoders (BERT, PubMedBERT), weighted top-k retrieval. ALTEGRAD course (IP Paris). *With P. Lemoine Vandermoere and A. Zenou.*
  [Repo](https://github.com/AntoineGilsonGH/Molecular-Graph-Captioning)
- **Deep learning for financial time series** — Supervised autoencoders and compact Transformers vs. LightGBM on the Jane Street dataset. *With M. Simoneau and M. Coppa.*
  [Repo](https://github.com/MaxCoppa/Advanced-ML)

### Statistics & model evaluation

- **Probability of flipped results** — Bayesian probability that the ranking of two models flips (accuracy, Dice), compared with McNemar's test. Code behind the *False Promises* paper's formulas.
  [Repo](https://github.com/AntoineGilsonGH/Probability-of-flipped-results)
- **Statistical assessment of trained models** — Notebook toolkit to assess one model or compare two: descriptive statistics, confidence intervals, paired parametric / permutation / bootstrap tests, Wilcoxon, McNemar.
  [Repo](https://github.com/AntoineGilsonGH/Statistical-Assessment-of-Trained-Models)
- **Zero-variance MCMC for GARCH models** — Control variates for variance reduction in Bayesian GARCH estimation, with LASSO selection for higher-order polynomials (Monte Carlo methods course).
  [Repo](https://github.com/AntoineGilsonGH/Monte-Carlo-GARCH)

### Applied data science

- **Alpine snow depth forecasting** — Designed a Codabench challenge: predict snow depth at J+7 across the French Alps from Météo-France SIM reanalysis data.
  [Repo](https://github.com/AntoineGilsonGH/AlpsSnowDepthPrediction)
- **Archelec topic modelling** — LDA, NMF and BERTopic on ~12,500 French legislative campaign manifestos (1981–1993).
  [Repo](https://github.com/AntoineGilsonGH/nlp-archelec)
- **ML for portfolio management** — FRED macroeconomic data and FOMC statement sentiment to predict multi-asset ETF returns (Ridge, LightGBM), with mean-variance portfolios and backtesting. *With C. Gadeau.*
  [Repo](https://github.com/AntoineGilsonGH/Machine-Learning-For-Portfolio-Management)
- **ARIMA forecasting of industrial production** — Box–Jenkins analysis in R of the French aeronautics and space production index; ARIMA(4,1,0) with bivariate forecast regions. *With V. Smague.*
  [Repo](https://github.com/AntoineGilsonGH/Series_Temporelles_Lineaires)
- **MLOps prediction market** — LightGBM pipeline on Kalshi event markets with MLflow, FastAPI, Docker and CI/CD. ENSAE. *With M. Coppa, M. Simoneau and A. Vautrin.*
  [Repo](https://github.com/MaxCoppa/MLOps-Prediction-Market)

---

**Tools:** Python (PyTorch, JAX, scikit-learn), R, SQL, Git, Docker, LaTeX

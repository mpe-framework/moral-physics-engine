# EFC v0.9.1 — Formal Spec & Torture Tests (QDHC / MPE Alignment)

**Core Morphism**
\[
\text{EFC}: \mathcal{E}_{n+1} \xrightarrow[\mathcal{C}]{\hat{\mathbb{E}}(\mathcal{A},\tau,\mathcal{Y})} \mathcal{F}_n=(\Pi,\Phi,D_0),\quad
\hat{\mathbb{E}}=\int_{\mathcal{E}}\big(\mathcal{A}\,e^{-\tau/\mathcal{Y}}\big)\,d\mathcal{C}
\]

**Cadence law:** \(f(\tau/\mathcal{Y})=\frac{1}{1+\kappa\,\tau/\mathcal{Y}}\), \( \Delta t_{\text{eff}}=f\,\Delta t \).

**Gate scope:** Dynamics always run; **projection** is gated:
- If \( \tau \le \tau_{\text{ref}} \):  
  \( \Phi \mathrel{+}= \text{total}\cdot e^{-\tau/\mathcal{Y}},\quad D_0 \mathrel{+}= \text{total}\cdot (1-e^{-\tau/\mathcal{Y}}) \)
- Else (refusal):  
  \( \Phi \mathrel{+}= 0,\quad D_0 \mathrel{+}= \text{total} \)

**Conservation (local):** \( \text{total}=\Phi_{\text{add}}+D_{0,\text{add}} \).

**Plural observers (REI):**  
\( \text{REI}_\Sigma = (\sum_i \text{REI}_i^p)^{1/p},\ 0<p<1;\quad K_{\text{eff}}=K\,(1+\beta\,\text{REI}_\Sigma^\gamma) \).

**Boundary set:** Ache invariance; refusal constraint; entropy gradient; surplus conservation; ledger monotone; cadence positivity.

**Falsifiers (headlines):**  
F1 clock decorrelation failure; F2 absent soft-echo band in high-τ ringdowns; F3 Φ-forbidden transitions observed.

**Status:** Copilot audit ✓ (coherence, stability, falsifiability). Grok torture suite ✓ (7/8; T6 pending REI streams).

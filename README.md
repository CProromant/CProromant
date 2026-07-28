# Conrado Proromant

Physician. I build open-source tools for health data.<br>
Santiago, Chile.

What interests me is what a dataset *doesn't* show you — and who goes missing
in the gap.

### `obsm` — Chile's mental health data, consolidated

Chile has no usable baseline for mental health. The public sources exist, but
scattered across agencies, inconsistent between years, half of them stuck in
PDF. `obsm` pulls them together and computes indicators nobody publishes.
First series: communal suicide mortality, 2002–2023, 346 communes — one
command reproduces it end to end.

The part I'd point at isn't the code. Total deaths for 2023 match the INE
yearbook exactly, and nine anomalies are documented rather than quietly fixed.
Five of those were my own bugs that threw no exception at all and would have
published numbers that looked perfectly reasonable.

### `riskaudit` — bias in the label, not the features

Most audits ask *how accurate is the model?* This one asks **who becomes
invisible because of the label we chose?** Train on a proxy — cost instead of
need, utilization instead of illness — and the bias lives in the target
variable, where standard fairness metrics can't see it.

---

MD, Pontificia Universidad Católica de Chile · MSc Data Science, UC Chile (in progress)<br>
[cproromant@gmail.com](mailto:cproromant@gmail.com) · [LinkedIn](https://www.linkedin.com/in/conradoproromant)

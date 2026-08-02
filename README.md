# Conrado Proromant

**Physician. I build open-source tools for health data in Santiago, Chile.**

---

### 📊 [`obsm`](https://github.com/CProromant/datos-salud-mental-chile) — Open data infrastructure for mental health in Chile

Chile has no usable baseline for mental health. Without one, no public policy can be evaluated — budget, gaps, and priorities get decided on anecdote or on figures from a decade ago. The data exists; it's scattered across agencies, inconsistent between years, half of it locked in PDF.

`obsm` is the infrastructure that baseline needs:
* **Consolidated & Traceable:** Public sources are normalized and published by commune and by month, with provenance recorded for every dataset and every run. 
* **Data-driven policy:** It's not a clinical app and doesn't touch identifiable patients. It exists so that arguments about mental health policy can be settled with numbers.
* **Ethical by design:** The first series (communal suicide mortality, 2002–2023) is published by grouper and *never* by method. One command reproduces it, and it won't publish at all if its reconciliation anchors don't hold (on top of strict statistical secrecy).

### ⚖️ [`riskaudit`](https://github.com/CProromant/risk-equity-audit) — Auditing label-choice bias in risk stratification

Health systems ration expensive programs with a model that decides who counts as high risk — usually defined as who will spend the most. Someone in real distress who never seeks care spends nothing, so the model reads zero and calls them low risk. The need was there; the label couldn't hold it.

`riskaudit` is a tool for measuring that bias:
* **Quantifying the gap:** Give it the scores a model produced and an independent measure of need, and it quantifies how much need the model leaves behind (weighted, with confidence intervals).
* **Agnostic application:** It doesn't care what the model predicts or where: a hospital's readmission model, an insurer's cost model, or a ministry's triage algorithm.

---

**🎓 Education & Contact**
* **MD**, Pontificia Universidad Católica de Chile 
* **MSc Data Science**, UC Chile *(in progress)*
* 📧 [cproromant@gmail.com](mailto:cproromant@gmail.com) | 💼 [LinkedIn](https://www.linkedin.com/in/conradoproromant)

[q]: https://github.com/CProromant/datos-salud-mental-chile/blob/main/docs/05-CALIDAD.md

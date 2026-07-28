# Conrado Proromant

Physician. I build open-source tools for health data.
Santiago, Chile.

### [`obsm`](https://github.com/CProromant/datos-salud-mental-chile) — Chile's mental health data, consolidated

No comparable communal series for mental health exists in Chile. The public
sources do — scattered across agencies, inconsistent between years, half of
them stuck in PDF. `obsm` consolidates them and computes indicators nobody
publishes. First series: communal suicide mortality, 2002–2023, 346
communes, age-standardized and empirical-Bayes smoothed. One command.

The part I'd point at isn't the code. Five reconciliation anchors run
before anything is written — 2023 deaths come out at 122,218, exact against
the INE yearbook — and if one fails, nothing publishes. [Nine anomalies][q]
are documented rather than quietly fixed. Five were my own bugs that threw
no exception: zero suicides across 27 years, from reading the wrong
diagnosis column. A commune that doesn't exist, because I validated the
format of the code and not the code. Numbers that would have looked
perfectly reasonable.

### [`riskaudit`](https://github.com/CProromant/risk-equity-audit) — bias in the label, not the features

Equalized odds, demographic parity, calibration — all conditioned on Y. If
Y is the corrupted object, they audit the model against the corruption and
come back clean. Train on cost instead of need and the bias sits exactly
where the metrics can't reach.

Seven functions, design-based CIs, ~99% coverage. On MEPS 2021–2023: among
the people a spend model deprioritizes, those in measured distress go on to
generate spending above what the model predicted — need it was blind to,
measured in the model's own currency, so the finding isn't circular.

---

MD, Pontificia Universidad Católica de Chile · MSc Data Science, UC Chile (in progress)
[cproromant@gmail.com](mailto:cproromant@gmail.com) · [LinkedIn](https://www.linkedin.com/in/conradoproromant)

[q]: https://github.com/CProromant/datos-salud-mental-chile/blob/main/docs/05-CALIDAD.md

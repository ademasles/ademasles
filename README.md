### Anton Demasles

I work on **world models and their calibration under distribution shift**: when a model trained on one machine is deployed on another, does it still know what it doesn't know?

Final-year engineering student at Mines Nancy (applied math & data science), dual degree with an MSc in Mathematical Engineering for Data Science (Université de Lorraine).
**Looking for a 6-month ML / research engineering internship from February 2027** (physical AI, world models).

#### Start here

- **[saac-jepa](https://github.com/ostertagmatthieu-dev/saac-jepa)**: code for *World Models for Cross-Machine CNC Transfer under Partial Sensor Overlap*, A. L. Bouaziz, M. Ostertag, **A. Demasles**. [arXiv:2609.16071](https://arxiv.org/abs/2609.16071) · poster at the BMVA Symposium on World Models (London, Nov 2026). My part: data pipeline and evaluation protocol, integrated by M. Ostertag. Reported as is: on the target machine the locked model beats persistence (RMSE 0.546 vs 0.654) but explains almost none of the variance (R² 0.012).
  - V2, multi-machine follow-up: **[cnc-world-models](https://github.com/ademasles/cnc-world-models)**, builds on saac-jepa as a dependency; first item, a scored survey of public CNC datasets for a new, unopened target machine.
- **[TODO: Project 3A repo]**: calibrated world models under distribution shift (PyTorch, in progress). Measuring and repairing the calibration loss caused by RevIN under cross-machine shift.
- **[les_zelles](https://github.com/ademasles/les_zelles)**: turns French construction tenders into cited, verified spec sheets. Rules engine + optional LLM + knowledge graph + MCP. Held-out F1 0.86 on real tenders at $0 per document; 105 tests, `mypy --strict`.
- **[scene-to-score](https://github.com/ademasles/scene-to-score)**: predicts a film scene's music in latent space, then generates it (OSSL-v2, 34k public-domain clips). [TODO: status / results]
- **[recipe-fusion](https://github.com/ademasles/recipe-fusion)**: multimodal recipe classification on Food-101 (ViT-B/16 + BERT), early vs late vs cross-attention fusion. [TODO: status / results]

#### Industry

- **Atos UK&I, London** (2026), AI Solutions Engineer intern: took an internal recruiting platform from a 3-day proof of concept to production on AWS (event-driven: Lambda, EventBridge, SQS, Aurora, CDK). Internal code, not open source.
- **Atos France** (2025–26), Strategy & Operations intern in a chief-of-staff role: AI presales redesign, technical scoping of a partnership with Poolside.

#### Community

- **[Hack the Worlds](https://hacktheworlds.fr/)** (2026), selection lead: picked 100 of 650+ master's and PhD applicants for a world-model hackathon backed by Yann LeCun.
- **Mines AI Society**, founder and president: the school's first AI society; leading a yearly physical-AI report.

PyTorch · Python · TypeScript · AWS

[arXiv](https://arxiv.org/abs/2609.16071) · [LinkedIn](https://linkedin.com/in/anton-demasles) · [ORCID](https://orcid.org/0009-0008-0640-6622) · demaslesa@gmail.com

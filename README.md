# Farzam Nikbakhsh Jorshari

I'm an MSc Computer Engineering student in the Artificial Intelligence curriculum
at the University of Padova, Italy, with graduation expected in March 2027.
My thesis work explores graph representations as structural priors for diffusion
models, in collaboration with researchers at the University of Pavia. This work
is in progress.

I'm interested in when structure helps a learning system, how to test that
against simpler alternatives, and how reliable its predictions remain when
conditions change. My main directions are graph representation learning,
diffusion models, trustworthy ML, and biomedical applications.

## Selected projects

These are independently developed personal projects, with code, experimental
controls, and limitations documented in each repository.

- [Graph-conditioned diffusion](https://github.com/DrNFRZM/graph-conditioned-diffusion) —
  Implemented mixed numerical/categorical diffusion and graph versus flat-feature
  conditioning on MovieLens 100K. Across ten seeds, the GNN has lower denoising
  loss but does not outperform flat conditioning overall. This is separate from
  my ongoing biomedical thesis work.
- [Tabular graph representation learning (GraphMix)](https://github.com/DrNFRZM/tabular-graph-representation-learning) —
  Compared GraphSAGE and feature-derived graphs with flat encoders and matched
  structure controls on UCI Adult. The five-seed study did not establish a
  benefit from neighbour information.
- [Reliable ML under shift](https://github.com/DrNFRZM/reliable-ml-under-shift) —
  Studied calibration, ensembles, and conformal prediction on Shifts Weather.
  Calibration improves NLL, while shifted-data coverage remains below the target.
  Saved predictions support evaluation without retraining.
- [Temporal-static graph fusion](https://github.com/DrNFRZM/temporal-static-graph-fusion) —
  Implemented static/time-series fusion on PhysioNet 2012 with concatenation,
  late-fusion, and graph controls. Static information helps; the tested graph
  connectivity shows no clear advantage.
- [Provenance-aware agent memory](https://github.com/DrNFRZM/provenance-aware-agent-memory) —
  Built a deterministic testbed for retrieval, verification, and quarantine.
  Forged provenance exposes limits of metadata-based defenses. All reported
  results use invented facts and a mock reader, not real LLMs.

## Technical work

Python; PyTorch and PyTorch Geometric; NumPy, SciPy, pandas and scikit-learn;
NetworkX; experimental evaluation, pytest, and GitHub Actions.

## Research background

My [bachelor's thesis on ML-based GNSS localization](https://thesis.unipd.it/handle/20.500.12608/76849)
was supervised by Prof. Stefano Tomasin at the University of Padova.
The [repository](https://github.com/DrNFRZM/gnss-localization-ml) links the deposited
thesis and citation; it does not contain the implementation.

I'm seeking funded PhD opportunities in AI and machine learning.

[GitHub](https://github.com/DrNFRZM) ·
[LinkedIn](https://www.linkedin.com/in/farzam-nikbakhsh-jorshari)

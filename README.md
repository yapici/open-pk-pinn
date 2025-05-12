# open-pk-pinn

**Open-source CMT-PINN model for plasma concentration-time profile prediction**

This project aims to create a public, transparent, and reproducible benchmark for machine learning-based pharmacokinetics (PK) prediction using compartmental physics-informed neural networks (PINNs).

Inspired by closed-industry papers that offer no usable tools, this project will:
- Build CMT-PINNs trained on public or simulated IV bolus PK data
- Benchmark performance using real metrics (MAPE, GMFE, etc.)
- Enable open collaboration, transparency, and iteration

## Current Features
- Baseline 1-compartment PINN model (PyTorch)
- Simulated toy dataset (IV bolus)
- Google Colab notebook with training and visualization

## Roadmap
- [ ] 2- and 3-compartment PINNs
- [ ] Public PK data ingestion (e.g. PK-DB)
- [ ] Reproducible benchmarking on test sets
- [ ] API or model serving demo

## How to Run
You can run the Colab notebook directly in your browser:
👉 [01_train_baseline.ipynb](notebooks/01_train_baseline.ipynb)

## License
MIT License

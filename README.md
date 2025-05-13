# open-pk-pinn

**Open-source CMT-PINN model for plasma concentration-time profile prediction**

This project aims to create a public, transparent, and reproducible benchmark for machine learning-based pharmacokinetics (PK) prediction using compartmental physics-informed neural networks (PINNs).

Inspired by closed-industry papers that offer no usable tools, this project will:
- Build CMT-PINNs trained on public or simulated IV bolus PK data
- Benchmark performance using real metrics (MAPE, GMFE, etc.)
- Enable open collaboration, transparency, and iteration

## Current Features
- Baseline 1-compartment PINN model (PyTorch)
- Public IV bolus dataset: oxypeucedanin 10 mg/kg (rat)
- Modular training and plotting notebook (`train_oxypeucedanin_10mgkg.ipynb`)

## Roadmap
- [ ] 2- and 3-compartment PINNs
- [ ] Additional compounds and dosing routes
- [ ] Reproducible benchmarking on test sets
- [ ] API or model serving demo

## How to Run
You can run the main notebook locally or in Google Colab:
👉 [`notebooks/train_oxypeucedanin_10mgkg.ipynb`](notebooks/train_oxypeucedanin_10mgkg.ipynb)

## Data
The dataset is publicly available and referenced in [`data/README.md`](data/README.md).

## License
MIT License

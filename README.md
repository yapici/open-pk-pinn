# open-pk-pinn

**Open-source CMT-PINN model for plasma concentration-time profile prediction**

This project builds a public, transparent, and reproducible benchmark for pharmacokinetic (PK) modeling using compartmental physics-informed neural networks (PINNs).

While recent publications have demonstrated the power of PINNs for predicting concentration-time profiles, most lack usable code or data. This project aims to change that.

## Goals

- Train and evaluate PINNs on public IV bolus PK data  
- Use 1-compartment ODEs to constrain model behavior  
- Benchmark predictive accuracy with MAPE, GMFE, and curve-fitting metrics  
- Build an open framework to foster collaboration and reproducibility  

## Current Features

- 1-compartment IV bolus PINN (PyTorch)  
- Real-world mouse PK dataset (oxypeucedanin, IV 10 mg/kg)  
- Modular code structure with reusable ODE and loss definitions  
- Cleaned Google Colab notebook for training and visualization  
- Version-controlled code and data (MIT-licensed)  

## Roadmap

✅ 1-compartment PINN with real PK data  
🟡 Training with additional public datasets (e.g. PK-DB)  
🟡 Robust benchmarking under data sparsity, noise  
🟡 2- and 3-compartment model support  
🟡 Model generalization to oral dosing, nonlinear PK  
🟡 Interactive API or demo interface  

## How to Run

You can run the training notebook directly in Colab:

👉 `notebooks/train_oxypeucedanin_10mgkg.ipynb`  
Or open it with: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yapici/open-pk-pinn/blob/main/notebooks/train_oxypeucedanin_10mgkg.ipynb)

## Data

The `data/` folder contains curated PK datasets with metadata and citations.  
See `data/README.md` for details.

## License

MIT License

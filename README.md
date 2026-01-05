 AMONN Smart Charging for Electric Vehicles

This repository contains the implementation of the Attention-based Multi-Output Neural Network(AMONN) for smart charging control of electric vehicles.  
It includes:
- Simulation framework: testing charging control strategies  
- Experimental test: OCPP-based closed-loop charger control with real vehicle and charger.  
- Data and models: sample datasets and pre-trained AMONN models.  
 
#By: M. Yasko, F. Tian, J. Driesen, and W. Martinez 
#From: KU Leuven/EnergyVille Thor Park 8310, Genk, Belgium.
#Last update: 2025-11-01

#Email: mohamed.yasko@kuleuven.be, yaskomht@gmail.com, yasko@ieee.org

---

## 📂 Structure
```
AMONN-smart-charging/
│
├── data/               # Example datasets (raw + processed samples)
├── models/             # Pretrained AMONN models (.pkl, .sd, scaler)
├── results/            # Example outputs (plots, logs)                # Source code
│   ├── simulation/     # Simulation framework
│   ├── experimental/   # OCPP-based experimental control
     



## `requirements.txt`

```
numpy
pandas
matplotlib
scipy
seaborn
torch
scikit-learn
joblib
websockets
ocpp
flask
werkzeug
asammdf
cantools
```

📜 License

- Code is licensed under the **MIT License**.  
- Models and datasets are licensed under the **Creative Commons Attribution 4.0 (CC BY 4.0)**.  


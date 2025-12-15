Traffic Flow Forecasting Ensemble: STL-GRU + MegaCRN

This repository implements a weighted average ensemble of STL-GRU and MegaCRN for spatio-temporal traffic forecasting on the MetrLA dataset. The ensemble leverages the complementary strengths of STL-GRU (temporal decomposition) and MegaCRN (memory-guided spatial-temporal modeling) to improve prediction accuracy.

Features:
- Multi-step traffic prediction for all sensors in the MetrLA network.
- Weighted ensemble of STL-GRU and MegaCRN outputs.
- Spatio-temporal heatmap visualization of traffic predictions and errors.
- Evaluation using MAE, MAPE, and RMSE for multiple forecast horizons.

References:
- STL-GRU: Kishor Bhaumik. [GitHub Repository](https://github.com/Kishor-Bhaumik/STLGRU/tree/main)
- MegaCRN: Deep Kashiwa. https://github.com/deepkashiwa20/MegaCRN/tree/main

These implementations were adapted and extended for the weighted ensemble described in this project.

Citations:
If you use this repository for your research, please cite the original papers:

@inproceedings{bhaumik2021stlgru,
  title={STL-GRU: A Spatio-Temporal Model for Traffic Forecasting},
  author={Bhaumik, Kishor and others},
  booktitle={AAAI},
  year={2021}
}

@inproceedings{kashiwa2022megacrn,
  title={MegaCRN: Memory-Guided Graph Convolutional Recurrent Network for Traffic Forecasting},
  author={Kashiwa, Deep and others},
  booktitle={NeurIPS},
  year={2022}
}

License:
This repository is released under the MIT License. Original STL-GRU and MegaCRN implementations retain their respective licenses.

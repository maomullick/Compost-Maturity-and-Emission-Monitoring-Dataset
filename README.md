# Compost Maturity and Emission Monitoring Dataset
{AUGMENTED} Compost Maturity Dataset from Khandakar et al., 2025


## Dataset Description:
This dataset by Mullick and Mufti et al. was used in the paper titled "*An Explainable and Scalable Framework for Compost Maturity Prediction Using Ensemble Learning and Conversational AI*" published in ACM NSysS 2025 as a short paper, contains 1,314 compost-monitoring samples derived from an original set of 452 observations collected through an Arduino- and ESP32-based wireless sensor system. The data capture physicochemical dynamics of compost maturity and were expanded using SMOTE/SMOGN to balance minority ranges while preserving temporal and biological consistency. Each record corresponds to a composting instance within one of 94 batches and includes measured or derived maturity indicators widely used in environmental monitoring and waste-bioprocess analytics.

## Features:
1. Day – Composting day at measurement time.
2. Temperature – Pile temperature (°C).
3. MC (%) – Moisture content.
4. pH – Acidity/alkalinity level.
5. C/N Ratio – Carbon–nitrogen ratio.
6. Ammonia (mg/kg) – Ammoniacal nitrogen concentration.
7. Nitrate (mg/kg) – Nitrate nitrogen concentration.
8. TN (%) – Total nitrogen.
9. TOC (%) – Total organic carbon.
10. EC (mS/cm) – Electrical conductivity.
11. OM (%) – Organic matter content.
12. T Value – Transformation value representing biodegradation progression.
13. GI (%) – Germination Index, a phytotoxicity indicator.
14. Score – Compost maturity score.
15. Batch – Assigned compost batch (1–94).
16. Synthetic – Binary flag indicating SMOTE-generated samples.
17. Source – Original or augmented label.

## Distribution Summaries:
All numerical variables include binned label–count summaries to support exploratory data analysis, outlier screening, and range-based modelling strategies. These distributions reveal wide variance in nitrogen compounds, organic matter decomposition rates, and moisture–temperature transitions across the composting timeline.

## Sampling Notes:
- 34% of samples originate from the real sensor-acquired dataset.
- 66% are SMOTE/SMOGN-generated to enhance representation across maturity stages.
- Time-continuous and batch-based patterns are preserved to enable forecasting, classification, and explainability analyses.


## The original dataset (452 samples) is available from Khandakar et al. (2025):
*https://www.sciencedirect.com/science/article/abs/pii/S0045790625000588*

## Citation for This Augmented Dataset (1,314 samples):
If you use this dataset, please cite:
```
@inproceedings{MullickandMufti2025,
  title={An Explainable and Scalable Framework for Compost Maturity Prediction Using Ensemble Learning and Conversational AI},
  author={Mullick, Mohammad Abu Obaida and Mufti, Abu Henaf Rashid Ahmad and Ratul, Rezaur Rahman and Noor, Jannatul},
  booktitle={Proceedings of the 12th International Conference on Next Generation Computing, Communication, Systems and Security},
  pages={29--34},
  year={2025},
  url = {https://doi.org/10.1145/3777555.3777574},
  doi = {10.1145/3777555.3777574}
}
```

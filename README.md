<p align="center">

  <h1 align="center"> Interpretable Hybrid Learning Model for Predicting Compressive Strength of Sustainable Pumice-Concrete Mixtures</h1>



## Abstract

Designing concrete mixes that are both strong and environmentally sustainable is a growing priority, especially when incorporating supplementary materials like pumice to reduce cement usage. This study investigates the effectiveness of Machine Learning (ML) models in predicting the 28-day compressive strength of pumice-based concrete. A curated dataset of 304 concrete mix designs was compiled from existing literature, and seven widely used ML algorithms—including Artificial Neural Networks (ANN), Decision Trees (DT), and boosting methods—were developed and compared. In addition, a hybrid ensemble model was created using the Grey Wolf Optimizer (GWO) to combine the strengths of the individual models. This hybrid approach achieved the highest predictive accuracy, reaching an R² of 0.950 and RMSE of 4.72 MPa on unseen test data, and improved the A-20 index by nearly 3% over the best-performing single model. To enhance model transparency and interpretability, SHAP analysis was employed, revealing that the water-to-powder ratio and superplasticizer content were the most influential features. The hybrid model not only demonstrated better generalization and reduced overfitting but also offers practical utility for performance-based concrete mix design. These findings highlight the potential of intelligent hybrid ML tools to support data-driven decision-making in sustainable concrete engineering.



## Installation


### 1. Clone the repository

```
git clone https://github.com/MLcode-Concrete/Concrete_strength
cd Concrete_strength
```


### 2. Open Jupyter Notebook files
```
Strength_Code.ipynb
```

### 3. Change your path Dataset & Run all cell
```
data = pd.read_csv('Path to Strength_ِDataset.csv')

```


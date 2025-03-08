# Covid-19 Machine Learning Project

## Description
This project aims to develop a machine learning model to predict and analyze the spread of the Covid-19 virus. The model will use various data sources to provide insights and forecasts.

## Features
- Data preprocessing and cleaning
- Exploratory data analysis
- Model training and evaluation
- Prediction and visualization

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/KHAROBUCHEBilal/Covid_2019_ML.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Covid_2019_ML
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the dataset and place it in the `data` directory.
2. Run the data preprocessing script:
    ```bash
    python preprocess.py
    ```
3. Train the model:
    ```bash
    python train.py
    ```
4. Make predictions:
    ```bash
    python predict.py
    ```
## Checklist de base (non-exhaustive)
    I. Analyse de la forme:
        + Identification de la target
        + Nombre de lignes et de colonnes
        + types de variables
        + Identification des valeurs manquantes
    II. Analyse du fond:
        + Visualisation de la target (Histogramme / Boxplot)
        + Comprehension des differentes variables (Internet)
        + Visualisation des relations features - target Histogramme / Boxplot
        + Identifaicaiton des outliers
    III. Pre-processing
        + Creation du train set / Test set
        + Elimination des Nan ; dropna(), imputation, colonnes <<vides>>
        + Encodage 
        + suppression des outliers nefastes au modele
        + Feature seleciton 
        + Feature Enginierring
        + Feature Scaling
    IV. Modelisation
        + Definir une fonction d'evaluation 
        + Entrainement de differents modeles
        + Optimisation avec GridSearchCV
        + Anlayse des erreurs et retour au Preprocessing / EDA
        + Learinng Curve et prise de decision

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions or suggestions, please contact [bilal.kharbouche99@gmail.com].

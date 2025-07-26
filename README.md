# ⚽ Football Player Potential Prediction

##  Project Description

This project applies **machine learning algorithms** to predict football player potential based on various performance metrics. Using Python libraries such as **Pandas**, **Scikit-learn**, and **TensorFlow**, the project leverages collected data from my football team with the help of my football coach.

The model analyzes multiple datasets to assess players' performance and predict their potential for future matches.

## 🛠️ Features

* Data analysis and preprocessing using **Pandas**
* Machine learning modeling with **Scikit-learn** (classification and regression models)
* Deep learning experimentation with **TensorFlow**
* Evaluation metrics to assess prediction performance
* Visualization of player metrics and model outputs

## 📂 Datasets

1. **`potential.csv`** – Contains detailed player metrics:

   * `pacrat`: Passing rate
   * `pacreu`: Successful passes
   * `lbrat`: Long ball rate
   * `lbreu`: Successful long balls
   * `interception`: Interceptions
   * `controlerate`: Ball control rate
   * `passedecisive`: Key passes
   * `aeriengagne`: Aerial duels won
   * `aerienperdue`: Aerial duels lost
   * `tir_en_dehord_de_surface`: Shots outside the box
   * `tir_six_metre`: Shots from six yards
   * `tir_surface_reparation`: Shots inside the penalty box
   * `potentiel`: Player potential score (target variable)

2. **`data.csv`** – Evaluation dataset for general potential:

   * `pd`: Defense power
   * `pm`: Midfield power
   * `pa`: Attack power
   * `resultat`: Overall potential result

## 📚 Libraries Used

* `pandas`: Data manipulation and analysis
* `numpy`: Numerical computations
* `scikit-learn`: Machine learning models and evaluation
* `tensorflow`: Deep learning models
* `matplotlib` & `seaborn`: Data visualization

## ⚙️ Installation & Execution

1. **Clone the project**

   ```bash
   git clone https://github.com/your-username/FootballPlayer-Potential_Prediction.git
   cd FootballPlayer-Potential_Prediction
   ```

2. **Open the Jupyter Notebook**

3. **Run the notebook cells** to train models and view predictions.

## 📊 Sample Output

* Predicted potential scores for players based on their metrics
* Comparison of actual vs predicted results
* Feature importance analysis and visualization

## 🚀 Possible Improvements

* Collect more player data across multiple matches
* Tune hyperparameters for better accuracy
* Build a web application to input player stats and predict potential in real time

## 👨‍💻 Author

Project developed by **Nada Ammar** in collaboration with the football coach of her team.

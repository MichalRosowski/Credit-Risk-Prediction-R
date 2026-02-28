# Credit Risk Modeling with H2O 🏦

An analytical project in R aimed at predicting customer default (credit risk) using machine learning algorithms.

## 🚀 About the Project
* The analysis was conducted on a financial dataset (`loan.csv`), with the primary goal of identifying high-risk customers (`bad_loan`).
* **Tools:** R, R Markdown.
* **Machine Learning:** Utilized the `h2o.ai` platform to build and evaluate predictive models (including Generalized Linear Models - GLM).
* **Evaluation & Business Value:** Optimized the model based on the AUC metric (achieved 0.7154). The project includes an in-depth analysis of class probabilities (`p0`, `p1`) and decision threshold tuning to minimize prediction errors, specifically focusing on the minority class (actual defaults).

## 📂 File Structure
* `credit_risk_modeling.Rmd` - The main notebook containing data preparation, model training, evaluation metrics, and business insights.

## ⚙️ How to Run
To view the code and results, you can open the `.Rmd` file in RStudio or Posit Cloud. Make sure to install the `h2o` package before running the environment:
```R
install.packages("h2o")
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Projekt analityczny w języku R, którego celem jest przewidywanie ryzyka kredytowego (Customer Default Prediction) przy użyciu algorytmów uczenia maszynowego.

## 🚀 O projekcie
* Analiza została przeprowadzona na zbiorze danych finansowych (`loan.csv`), a jej głównym celem była identyfikacja klientów wysokiego ryzyka (`bad_loan`).
* **Narzędzia:** Język R, R Markdown.
* **Machine Learning:** Wykorzystano platformę `h2o.ai` do budowy i oceny modeli predykcyjnych (w tym uogólnionych modeli liniowych - GLM).
* **Ewaluacja i Wartość Biznesowa:** Zoptymalizowano model pod kątem metryki AUC (osiągnięto 0.7154). Projekt zawiera dogłębną analizę prawdopodobieństw klas (`p0`, `p1`) oraz dostrajanie progu decyzyjnego w celu minimalizacji błędów predykcji, ze szczególnym uwzględnieniem klasy mniejszościowej (rzeczywiste braki spłaty).

## 📂 Struktura plików
* `credit_risk_modeling.Rmd` - Główny notatnik zawierający przygotowanie danych, trenowanie modelu, metryki ewaluacyjne i wnioski biznesowe.

## ⚙️ Jak uruchomić?
Aby przejrzeć kod i wyniki, możesz otworzyć plik `.Rmd` w RStudio lub Posit Cloud. Upewnij się, że zainstalowałeś pakiet `h2o` przed uruchomieniem środowiska:
```R
install.packages("h2o")
```

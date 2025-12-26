## Fatal Force Analysis

A data analysis and machine learning project analyzing fatal police shootings in the United States.  
This project explores demographic and situational factors associated with fatal force incidents and applies supervised learning models to examine patterns related to victim race.

### Research Focus
- Investigated whether victim race can be predicted from non-racial contextual features in fatal police shooting data.
- Applied and compared multiple supervised learning models with different inductive biases:
  - Multinomial Logistic Regression using armed status
  - Random Forest using geographic information (state-level data)
  - Gradient Boosting using age as a numerical feature
- Designed feature–model pairings to reflect different assumptions:
  - Linear probabilistic relationships (Logistic Regression)
  - Non-linear interactions and regional patterns (Random Forest)
  - Error-focused boosting on potentially imbalanced demographic data (Gradient Boosting)
- Evaluated model performance using classification metrics and confusion matrices, with emphasis on minority class behavior.
- Emphasized interpretability, feature relevance, and ethical considerations when modeling sensitive attributes such as race.

### Project Report
- **Full Analysis Report (PDF)**:  
  [Fatal Force Analysis – Project Report](https://drive.google.com/file/d/1hqnANBx8tzWUXRBR2avoi7WkS-poqOkc/view?usp=sharing)

### Portfolio Page
- **Interactive Portfolio & Visual Summary**:  
  [Project Portfolio Page](https://drive.google.com/file/d/1HVP1nOJxqwZGMMPHGWbU6OMDSQTKDC78/view?usp=sharing)

### Tech Stack
- Python, NumPy, Pandas
- Plotly / Seaborn
- Scikit-learn
- Google Colab

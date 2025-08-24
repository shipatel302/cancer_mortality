# END-TO-END ANALYTICS FOR CANCER MORTALITY
Cancer Mortality & Social Determinants
EDA • ANOVA/Tukey • ML Pipeline (OneHot + Random Forest)

A reproducible analysis of U.S. state-level cancer death rates and social determinants of health (diet, smoking, BMI, disability, insurance, etc.). The project includes tidy EDA, inferential statistics (one-way ANOVA with Tukey HSD), and a scikit-learn Pipeline with OneHotEncoder, StandardScaler, K-Fold GridSearch, and RandomForest (plus feature importance).

🔎 Highlights

EDA: Clean 51-row state panel; engineered food_consumption = mean(Fruits≥1/day, Vegetables≥1/day); summarized by state & region.

Statistics: Region is significantly associated with cancer death rate (ANOVA); Tukey HSD identifies which regional pairs differ.

ML: Pipeline (OneHot + RF, 5-fold GridSearchCV) achieves ~0.82 accuracy; top drivers include language at home, disability (<66), fruit intake, healthy-weight BMI, smoking.

Actionability: Target higher-risk regions and prioritize levers like cessation, produce access, BMI/fitness, and navigation support for linguistically diverse communities.
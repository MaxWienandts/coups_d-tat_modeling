# coups_d-tat_modeling
- Autumn Dorsey
- Loralee Ryan
- Max Wienandts
- Ronan Fonseca

This study tries to determine the most relevant factors for predicting coups d’état using data for 943 coup
events from 1945 to 2019, using four different modeling techniques, logistic regression, decision trees,
LightGBM and XGBoost. Models had similar accuracy performance in the test set, with Logistic
Regression having the best performance in terms of classification accuracy on the testing set. Using
SHAP metrics to compare variable impact between models, the results showed that all models selected
the same set of predictors as their top four most important. These four factors were related to whether or
not the coup was initiated by (1) a dissident group outside the current government, (2) military actors who
are formally part of the government, (3) a faction inside the existing government, and (4) a popular revolt.
Though each of the models did not exactly coincide in the order in which these factors were ranked, all of
them considered the presence of a dissident group as a coup initiator to be far more important than the
other predictors.

Motivation and Context

Coups are political events that significantly change the course of a country and its people. The
overt-hrowing of the current government can signify the beginning of free, peaceful times, or the
beginning of authoritarian periods marked by human rights violations. Given their impact, and the fact
that coups still happen to this day, it is worth studying what factors are most relevant for determining a
coup's success, so that we can better analyze those coups that happened in the past, and understand what
can predict those that will happen in the future. This study is particularly meaningful for the members of
this group, given the tumultuous processes for the latest presidential elections in Brazil and the United
States.

Problem Statement:

Our problem statement is: Which variables are most important to
have a successful coup?

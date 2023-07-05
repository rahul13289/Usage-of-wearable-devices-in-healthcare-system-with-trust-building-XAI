# Usage-of-wearable-devices-in-healthcare-system-with-trust-building-XAI

We are going to analyse the data from wearable devices connected with healthcare system. The actual parameter are introduced such as age,cholesterol,heart rate,blood pressure,o2,temperature as a result we will be predicting whether the patient is on normal condition by evaluating the available dataset.The technology has an real time application of measuring medical parameters of a patient and making a justified report of him/her health condition on certain conditions because of this feature the doctors as well as care taker of the patient can monitor the health of patient constantly.

In this paper, we are measuring and analysing the sample data discharged from wearable devices for health care system. The data acquire parameters like age, cholesterol level, blood pressure, heart rate, oxygen level of the patient by training and testing the prediction of normal condition of patient was founded. The supervised algorithm and unsupervised algorithm like logistic regression,knn,svm are implemented and accuracy are successfully probed for these algorithm. Best accuracy was found in knn algorithm with 94%.

Various explainable ai algorithm like shap,lime and explainable boosting machine are utilized. The performance of those algorithms and execution time of code are determined with plot.

Explainable AI:
The explainable AI concept was implemented in project to develop trust in AI model. The AI model before using XAI can be termed as black box.
There are three main parts of explainable ai:
1)Prediction Accuracy
(*)Lime model is used for adding instance to prediction accuracy
2)Traceability
3)Decision Under
(*)Applications on Dashboard design for business purpose
Model Investigation:
There are 4 parts of tracking:
(*)Deployment status
(*)Fairness
(*)Quality
(*)Drift
Implemented models in explainable ai are:
Lime:
	Local Interpretable Model-agnostic Explanations (LIME) is one of the most popular Explainable AI (XAI) methods used for explaining the working of machine learning and deep learning models. 

	LIME can provide model-agnostic local explanations for solving both regression and classification problems and it can be applied with both structured datasets and even with unstructured datasets like text and images

SHAP:

SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions.


EBM:
EBM is a glassbox model, designed to have accuracy comparable to state-of-the-art machine learning methods like Random Forest and BoostedTrees, while being highly intelligible and explainable. EBMs are a form of Generalized Additive Models (GAM), formalized by Trevor Hastie and Robert Tibshirani. 




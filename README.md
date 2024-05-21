# Well-tempered medical prompt engineering for explainable extubation (medpromptforXAI)
This study proposes a method to enhance the interpretability of XGBoost-based models in the field of medical artificial intelligence by utilizing prompt engineering to improve the interpretability of SHAP and given data.

### Project Structure
* prompt folder: Contains the before tempering prompt and after tempering prompt.
* result folder: Contains the qualitative results of the study. Includes an Excel file (Result.xlsx) comparing the outputs of the before and after tempering prompts, highlighting the improvements in specific aspects such as variable referencing accuracy, selection of top 3 variables based on SHAP values, handling of missing value variables, and focus on specific topics. The Excel file also includes test results of TP 10, TN 10, FP 10, and FN 10.

### Research Overview
This study was conducted in the following steps:

1. Development of an extubation failure prediction model using XGBoost
2. Interpretation of model prediction results using SHAP
3. Improvement of SHAP-based explanations through prompt engineering
4. Generation of model explanations using the before and after tempering prompts
5. Qualitative evaluation and comparison of the generated explanations to identify improvements in specific aspects

The following principles were applied during the prompt engineering stage:

* Providing terminology/descriptions for variables
* Instructing to select top 3 variables based on SHAP
* Preventing generation of random values for missing value variables
* Focusing on specific topics instead of general medical knowledge

### Results
The study results, as documented in the Result.xlsx file, demonstrate that the model explanations generated using the after tempering prompts were qualitatively better than those generated using the before tempering prompts. The comparative analysis highlights improvements in variable referencing accuracy, selection of top 3 variables based on SHAP values, handling of missing value variables, and focus on specific topics. This suggests that prompt engineering can contribute to enhancing the explainability of medical AI models by generating more accurate and relevant explanations.

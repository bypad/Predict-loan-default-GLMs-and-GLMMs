# Predict-loan-default-GLMs-and-GLMMs

OBJECTIVE: Build a statistical model to predict loan default based on information known at the time of loan application.

DATA: The historical lending data includes the training, validation, and testing set which detail 20 possible covariate. An extended version of the data is also provided that includes additional information about the date the loan was issued and the approximate address (state and leading zip code digits).

KEY QUESTIONS:

Build a generalised linear model (GLM) to address questions:
1. How does your new model perform compared to the one you used previously? How can it be expected to perform on new loan applications? For this, you must use the training and validation data used in the previous benchmark.
2. What are the important variables in this model and how do they compare to variables that are tra- ditionally important for predicting credit risk in the banking sector? One regulatory requirement for lenders is that they need to to clearly explain how a loan application was assessed. To demonstrate to management that this can be achieved, clearly interpret all covariates in your model in terms of their effect on predicting credit risk.

Build a generalised linear mixed effects model (GLMM) to address questions (use the extended data version):

3. Can accounting for this variation (e.g., state/zip-code and time) improve performance benchmarks?
4. Are there any surprising differences in variables that are important for predicting credit risk? This is again essential for regulations.
5. Does credit risk change over time or between states? This is not something the bank has previously investigated and results may inform modified loan policies in the future.

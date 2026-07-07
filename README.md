# Heart-Disease-Prediction
Built a neural network that predicts heart disease from patient health metrics with 90% test accuracy.
Because missing a sick patient is dangerous in medicine, I custom-tuned the model's decision threshold to maximize safety successfully catching 94% of all heart disease cases (94% Recall) while keeping false alarms very low (89% Precision).

Final Results (Test Data):

Overall Accuracy: 90%

Recall (Sensitivity): 94%

Precision: 89

Key Features:

Used One-Hot Encoding and Z-score scaling without any data leakage.

Used L2 regularization and a stable learning rate to make the model robust and stable.

Adjusted the final classification threshold to prioritize clinical screening safety.

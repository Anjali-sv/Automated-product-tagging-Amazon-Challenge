#INITIAL FINETUNING
-Download dataset. Dataset is publicly available and provided by Amazon for Amazon ML Challenge 
-Preprocess train data preprocess_train.py
-Creating JSON for finetuning with LLaMA-Factory dataprep.py
-Follow guidelines given in docs of LLaMA-Factory to register
-For finetuning follow finetune.ipynb. Settings for finetuning will be registered using WebUI

#INFERENCING OF MODEL
-Run inference.py
-Post Processing postprocess.py
-Evaluation Metric: F1 Score

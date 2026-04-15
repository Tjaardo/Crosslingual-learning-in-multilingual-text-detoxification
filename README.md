# Crosslingual-learning-in-multilingual-text-detoxification
This is the code for training and evaluating models for multilingual text detoxification


Our model Training and Evaluation Pipeline consists of three Notebooks per model
We have three different model approaches, so there are three Pipelines.

Multilingual Training:
- run Qwen3_Finetuning.ipynb with multiple languages
- run Qwen3_prepare_evaluation.ipynb
- run Evaluation.ipynb

English-Only Training:
- run Qwen3_Finetuning.ipynb with just the english dataset split
- run Qwen3_prepare_evaluation.ipynb
- run Evaluation.ipynb

English + Toxic Token Training:
- run Qwen3_TOX_Finetuning.ipynb with just the english dataset split
- run Qwen3_TOX_prepare_evaluation.ipynb
- run Evaluation.ipynb

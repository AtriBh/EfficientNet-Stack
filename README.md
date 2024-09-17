
---

# EfficientNet Fine-tuning and Stacking Ensemble

This repository contains two Jupyter notebooks related to fine-tuning and ensembling EfficientNet models for classification tasks.

## Files

1. **`EfficientNet-Finetuning.ipynb`**  
   This notebook demonstrates how to fine-tune various EfficientNet models on your custom dataset. It includes:
   - Loading pre-trained EfficientNet models.
   - Applying custom modifications such as adding Dense and Dropout layers.
   - Training and fine-tuning the models using a specific loss function and optimizer.

2. **`Efficientnet-ensemble.ipynb`**  
   This notebook illustrates how to create an ensemble of the fine-tuned EfficientNet models using a stacking method. It involves:
   - Aggregating the outputs of multiple base learners (EfficientNet models).
   - Feeding the base learner outputs into a meta-learner for final predictions using stack generalization.
   - Evaluation of the ensemble model on test data.

If the Jupyter notebooks are not rendering correctly on GitHub, you can view them directly using [nbviewer](https://nbviewer.org/), which supports rendering `.ipynb` files.

Simply copy the notebook URL into nbviewer, and it will display the content properly.

---

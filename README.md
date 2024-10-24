Here’s a revised version of your README file with clearer structure and improved formatting:

---

# Fire Scar Detection Using Prithvi_ViT_100

We trained, fine-tuned, and evaluated the **Prithvi_ViT_100** model on the **Fire_Scar** dataset. We utilized **Weights and Biases (wandb)** for tracking accuracy scores and losses, and calculated the **Intersection over Union (IoU)** metric to compare the model's predictions with the ground truth masks.

## Model Training Summary

- **Model:** Prithvi_ViT_100 (Vision Transformer architecture for image classification).
- **Dataset:** Fire_Scar dataset.
- **Metric:** Intersection over Union (IoU).
- **WandB:** Used to track accuracy scores, losses, and other key metrics.

### Tuning Details

- **Epochs Trained:** 50
- **Model Accuracy:** 97.486%
- **Learning Rate:** 0.0003

## Tools and Frameworks Used

- **Prithvi_ViT_100:** A Vision Transformer model architecture used for image classification tasks.
- **Weights & Biases (wandb):** Experiment tracking, visualizations, and logging tool used to monitor model performance.
- **TerraTorch:** Deep learning framework used to build, train, and fine-tune the model.

---

## Hackathon Evaluation Requirements

Participants must provide the following:

### 1. **Training Notebook:**

- A Jupyter Notebook for model training.
- Must include the trained model weights, logs, and metrics.
- Ensure the notebook is easy to run and well-documented for the judges.

### 2. **Model Improvement Documentation:**

- A comprehensive list of attempts to improve model performance.
- Include results and explanations for each attempt.
- Judges will evaluate the effort, decision-making process, and final results.

### 3. **Performance Metrics Calculation:**

- **Metric:** Intersection over Union (IoU).
- Use the formula:

  $$ \text{IoU} = \frac{\text{True Positive}}{\text{True Positive} + \text{False Positive} + \text{False Negative}} $$

- Refer to `inference_terratorch.ipynb` for model testing details.

### 4. **Inference Notebook:**

- A Jupyter Notebook for running model inference.
- The test dataset will not be provided but will follow the same format as the training/validation data.
- Ensure all inference steps are clearly shown and easy to follow.
- The notebook will be used by judges to calculate the IoU score with a held-out set of data (expect less than 100% accuracy).

### 5. **TerraTorch Documentation:**

- Refer to `config_explainer.md` for detailed configuration explanations.
- Understand the configuration for potential model improvements.
- Use the **TerraTorch Quick Start documentation** to run model inference and understand configuration options.

---

## Prithvi_ViT_100 Model Training and Parameter Tuning

During our experimentation with the **Prithvi_ViT_100** model on the **Fire_Scar** dataset, we achieved an accuracy of **98.40%**. WandB was used for experiment tracking to monitor accuracy scores and losses, and IoU was computed to measure the performance.

### Model Tuning Overview:

- **Model Accuracy:** 97.40%
- **Training Epochs:** 50
- **Learning Rate:** 0.0003

---

## Metric Used: IoU Calculation

The **Intersection over Union (IoU)** was used as the primary performance metric to evaluate the model's segmentation accuracy. The formula for IoU is:

$$ \text{IoU} = \frac{\text{True Positive}}{\text{True Positive} + \text{False Positive} + \text{False Negative}} $$

# Final Accuracy Score (Wandb):
![Screenshot 2024-10-24 105948](https://github.com/user-attachments/assets/13466738-25ba-4aa0-b377-8307ca7f698d)


# Final Model Results:
![image](https://github.com/user-attachments/assets/421e679c-6d96-429a-9051-b08c78bc4fca)

---

### Final Notes

Ensure that all notebooks, logs, and trained model weights are well-organized and easy to follow for the judges. The documentation should clearly explain each step in the model training, fine-tuning, and inference process.


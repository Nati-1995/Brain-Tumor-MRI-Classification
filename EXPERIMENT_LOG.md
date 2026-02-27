# MRI Brain Tumor Classification - Experiment Log

**Model Architectures:** ResNet50 & EfficientNetB0
**Target:** Binary (Tumor/No Tumor) & Multiclass (4 Types)

---


**[2026-02-24 09:59:41]** Ran 5-fold cross-validation on binary model, mean F1: 0.883.

**[2026-02-24 11:19:04]** Model Checkpoint: Validation F1 improved from 0.8512 to 0.8877. Saving model.

**[2026-02-24 12:44:03]** Applying CLAHE preprocessing to validation set, contrast improved

**[2026-02-25 13:04:32]** Epoch 12/50 - loss: 0.412 - accuracy: 0.81 - val_loss: 0.425 - val_accuracy: 0.80

**[2026-02-25 17:01:14]** Preprocessing: resized all inputs to 224x224, normalized to ImageNet stats.

**[2026-02-26 11:26:25]** Gradio interface successfully routed to EfficientNetB0 backend.

**[2026-02-26 20:41:46]** Switched optimizer to Adam with weight decay, smoother loss curve.

**[2026-02-27 10:41:27]** Epoch 38/50 - loss: 0.298 - accuracy: 0.88 - val_loss: 0.312 - val_accuracy: 0.87

**[2026-02-27 11:42:10]** Switched optimizer to Adam with weight decay, smoother loss curve.

**[2026-02-27 14:35:13]** Binary model converging faster than multiclass — expected given task simplicity.

**[2026-02-27 19:40:35]** Ran 5-fold cross-validation on binary model, mean F1: 0.883.

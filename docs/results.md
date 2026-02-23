# Results

## Model Evaluation Summary
The project evaluated multiple AI models for bitewing radiograph quality classification and comparison.

The report presents performance metrics including:
- Accuracy
- Precision
- Recall
- F1-score

## Main Finding
The report states that **EfficientNetB0** achieved the best overall performance among the evaluated models.

It also highlights that:
- **MobileNetV3 Small** performed strongly and offered a good balance between efficiency and accuracy.
- **Transformer-based models (ViT and hybrid variants)** required careful adaptation and did not outperform the CNN-based baseline in this multimodal setup.

## Reported Performance (Table 5.2)
The report includes the following models in the comparison:
- MobileNetV3 Small
- EfficientNetB0
- Vision Transformer (ViT)
- EfficientNet + ViT Hybrid
- MobileNetV3 + ViT Hybrid
- Custom ViT-style

## Training Configuration
The report also includes a hyperparameter comparison table (learning rate, optimizer, batch size, epochs, dropout) to ensure fair comparison across models.

## Interpretation
Based on the report discussion, the project results support using deep learning for automated bitewing image quality assessment, with EfficientNetB0 emerging as the most accurate model in this study.
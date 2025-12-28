# Datasets and Practical Considerations for Plant Disease and Pest Detection

## Commonly Used Datasets
- PlantVillage: widely used benchmark with controlled, lab-style images.
- Custom field datasets: capture real-world variability but are often smaller and noisier.
- Crop-specific datasets focusing on tomato, potato, and rice diseases.

## Common Pitfalls
- Data leakage due to similar backgrounds across training and test images.
- Overfitting to lab conditions, leading to poor field performance.
- Class imbalance between healthy and diseased samples.
- Background bias where models learn non-plant cues.

## Field Deployment Considerations
- Variable lighting conditions significantly affect model accuracy.
- Occlusion and complex backgrounds are common in real-world settings.
- Mobile and edge deployment require lightweight architectures.
- Robust models must generalize across geography, seasons, and camera quality.

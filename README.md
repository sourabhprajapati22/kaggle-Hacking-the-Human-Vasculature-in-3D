# kaggle-Hacking-the-Human-Vasculature-in-3D
The goal of this competition is to segment blood vessels. You will create a model trained on 3D Hierarchical Phase-Contrast Tomography (HiP-CT) data from human kidneys to help complete a picture of vasculature throughout a body.
[DataLink!](https://www.kaggle.com/competitions/blood-vessel-segmentation/data)

## Evaluation
We evaluate submissions using the surface dice metric with a tolerance of 0.0.

You can find the code for the metric in this notebook: Surface Dice Metric.

## Files

 - kidney-train-1.ipynb: Contains the training pipeline for kidney vein segmentation, including data preprocessing, model training, and evaluation.

 - kidney-inference-1.ipynb: Handles inference on new images using the trained model.

## Results

The trained model predicts vein structures in kidney images, visualized as segmentation masks.

## Citation  
If you use this work, please cite it as shown in [`CITATION.bib`](CITATION.bib).

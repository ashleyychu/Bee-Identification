# Bee-Identification

This is an adapted notebook from Vencerlanz09. "Pests Classification Using EfficientNetV2-L." Kaggle, 2022, https://www.kaggle.com/code/vencerlanz09/pests-classification-using-efficientnetv2-l.

## Project summary:

🐝yond Recognition: Bee vs. Wasp Identification Using Deep Convolutional Neural Networks and Transfer Learning

Pollinators such as bees play a critical role in sustaining ecosystems and global agriculture, yet their populations are rapidly declining due to environmental stressors. Accurate identification and tracking of bees are essential for conservation efforts but remain challenging due to their small size and visual similarity to other insects, such as wasps. In this project, we leverage the power of convolutional neural networks (CNNs) and transfer learning to automate the classification of bees, wasps, other insects, and non-insect images. Using a pre-trained EfficientNetV2L model fine-tuned for this task, we achieved robust performance, enabling rapid and accurate classification. Our work also explored the use of principal component analysis (PCA) to analyze the salient features learned by the model and gain deeper insights into the classification process. Inspired by related studies and real-world challenges, we designed our dataset to include diverse images under varying conditions to improve model generalizability. This research demonstrates the potential of deep learning to outperform human accuracy in insect identification, paving the way for more accessible and scalable tools for pollinator conservation and ecological research.

## How to run

We recommend uploading all files (Jupyter notebook, dataset folder and training logs) to datahub/JupyterLab with GPU for best environment compatibility as we ran into issues running this locally. Training logs are provided so that you don't have to retrain the classifier head and just access saved weights for analysis. Please refer any questions to the project creators.
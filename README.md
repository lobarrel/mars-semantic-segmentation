# Semantic segmentation of Mars terrain images

This was the second challenge of the Artificial Neural Networks and Deep Learning course [2024-2025] of Politecnico di Milano.

## Goal
This is a semantic segmentation problem, where the goal is to assign the correct class label to each mask pixel. We were provided with a dataset containing 64x128 grayscale images of Mars terrain where pixels are categorized into five classes, each representing a different type of terrain.
The dataset consists of segmented images from Mars terrain. Each image is paired with a mask representing the class of each pixel:
- 0: Background
- 1: Soil
- 2: Bedrock
- 3: Sand
- 4: Big Rock

![mars_terrain](https://github.com/user-attachments/assets/efa62d04-00d9-442c-a21f-b433fc57cbba)

⚠️ Please note that for this challenge all pretrained models were forbidden. Neural networks must be trained from scratch, without relying on existing trained architectures.

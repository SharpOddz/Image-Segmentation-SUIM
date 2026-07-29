# Underwater Image Segmentation on SUIM Dataset

[View the Full Written Report](CS_685_Final_Project_Report.pdf)

## Project Description
This project implements a U-Net model from scratch to perform image segmentation on the Semantic Segmentation of Underwater Imagery dataset (SUIM). Specifically, the U-Net built for this project will not be using a pre-trained encoder but will still follow the standard encoder-decoder structure of a U-Net. The SUIM dataset contains pixel-level ground truth masks for each image. This allows for the U-Net to be evaluated on its ability to assign every pixel to one of eight classes. The goal of the project is to evaluate the performance of the built from scratch U-Net and compare it to SUIM-Net and other U-Net variations, primarily using mean intersection over union (mIOU).

## Model Architecture

<img width="758" height="549" alt="image" src="https://github.com/user-attachments/assets/d33e1fc9-e027-4cac-8933-ebaf881b0192" />

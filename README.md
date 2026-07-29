# Underwater Image Segmentation on SUIM Dataset

[View the Full Written Report](CS_685_Final_Project_Report.pdf)

## Project Description
This project implements a U-Net model from scratch to perform image segmentation on the Semantic Segmentation of Underwater Imagery dataset (SUIM). Specifically, the U-Net built for this project will not be using a pre-trained encoder but will still follow the standard encoder-decoder structure of a U-Net. The SUIM dataset contains pixel-level ground truth masks for each image. This allows for the U-Net to be evaluated on its ability to assign every pixel to one of eight classes. The goal of the project is to evaluate the performance of the built from scratch U-Net and compare it to SUIM-Net and other U-Net variations, primarily using mean intersection over union (mIOU).

## Model Architecture

<img width="758" height="549" alt="image" src="https://github.com/user-attachments/assets/d33e1fc9-e027-4cac-8933-ebaf881b0192" />

## Visual Results

<img width="780" height="499" alt="image" src="https://github.com/user-attachments/assets/ea65c079-6775-454f-9824-5ab77fa4ff7b" />

<img width="668" height="418" alt="image" src="https://github.com/user-attachments/assets/c38307b7-c3d9-4f0e-937e-cbe8cd826514" />

## Evaluation
The results for the model on the training, validation, and test IOU are shown in the figure below. The model performs the strongest on the most dominant class in the dataset: background. It performs the worst by a large margin on aquatic plants. The model generally does better on the background classes than the foreground classes. This is likely due to the dominance of background pixels in the images. The five foreground classes are: Human Diver (HD), Wrecks/Ruins (WR), Robots (RO), Reefs/Invertebrates (RI), Fish/Vertebrates (FV).

<img width="681" height="638" alt="image" src="https://github.com/user-attachments/assets/b945cbce-38bb-4873-b542-6f23502e924b" />

# YOLOv8-AF: Ground Pit Detection for Border Security

**YOLOv8-AF** is a customized deep learning model designed for efficient and accurate ground pit detection using aerial imagery. This model aims to enhance border security by autonomously identifying potential underground tunnels that pose security risks, such as illegal immigration and smuggling.

## Features
- **High Accuracy**: Achieves over 95% accuracy and a mAP of 0.895 on the Ground Pit Image Dataset (GPID).
- **Real-Time Processing**: Capable of processing 116.28 frames per second, making it suitable for real-time surveillance applications.
- **Custom Architecture**: Streamlined YOLOv8 with optimized layers for fast and efficient pit detection.

## Dataset
We use the **Ground Pit Image Dataset (GPID)**, consisting of 300 aerial and satellite images of ground pits in various terrains.

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-repo/YOLOv8-AF
cd YOLOv8-AF
pip install -r requirements.txt
```
## Usage
Train the model on your dataset:
```bash
python train.py --dataset GPID --epochs 350
```
## Run inference:
```bash
python detect.py --image <image_path>
```
## Results
- Accuracy: 95%
- FPS: 116.28
- mAP: 0.895

## Contributors
- Debendra Muduli
- Aman Ujwal Toppo
- Vikrant Singh
- Mahendra Singh
- Divy Prakash Tiwari

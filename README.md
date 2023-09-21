# Marine_debris_detection
Marine debris detection using Satellite Images.
# Marine Debris Detection using Satellite Images

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project focuses on the detection of marine debris using satellite images of the Atlantic Ocean and Mumbai Harbor. Marine debris, including plastic waste and pollutants, poses a significant threat to the environment. By leveraging satellite imagery and OpenCV, we aim to identify and visualize marine debris in these specific regions.

## Project Overview
- Utilize satellite images of the Atlantic Ocean and Mumbai Harbor.
- Implement an image processing pipeline using OpenCV for debris detection.
- Develop a user-friendly interface for uploading and analyzing satellite images.
- Display detected marine debris regions on the input images.
- Provide summary statistics on the extent of marine debris in the selected regions.

## Dataset
The dataset for this project consists of publicly available satellite images of the Atlantic Ocean and Mumbai Harbor, obtained from [earthexplorer.usgs.gov]. These images serve as the basis for detecting marine debris.

![Sample Dataset](![image 1](https://github.com/purvadhamodikar/Marine_debris_detection/assets/129665527/8ce30c15-e04e-4fda-a887-7d42161591cb)
)

## Methodology
1. Image Preprocessing: The satellite images undergo preprocessing, including noise reduction and contrast enhancement.
2. Debris Detection: OpenCV is used to detect debris in the images through techniques such as contour detection and color-based segmentation.
3. Visualization: Detected debris regions are highlighted on the input images for easy identification.
4. Summary Statistics: The project generates statistics on debris concentration in the selected regions.

## Requirements
- Python 3.7+
- OpenCV 4.0+
- Flask (for the web interface)


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/purvadhamodikar/Marine_debris_detection
   cd marine-debris-detection

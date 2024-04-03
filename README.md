# Tracify2.0 : Real Time Object Tracking and Tracing 

Tracify2.0  is the updated version of Tracify where some feature are added :-
-  Multiple object tracking at single frame / previous version is detecting only single object 
-  Trace the path of object till Multiple frames
-  YOLOv9 is used here previous version  was based on YOLOv5

## Introduction

Tracify 2.0  utilizes computer vision techniques for real-time object detection and tracking with YOLOv9 and DeepSORT algorithms. With Tracify, you can monitor and track objects or individuals within a specified area with high accuracy and efficiency.it is versatile surveillance system that combines object detection and multi-object tracking (MOT) to provide enhanced security and monitoring capabilities.

## Features

- **Real-time Object Detection**: Tracify employs YOLOv5, a highly efficient object detection model, to detect objects in real-time from various input sources such as webcams, video files, or live streams.

- **Multi-object Tracking (MOT)**: DeepSORT is integrated into Tracify to perform multi-object tracking, allowing the system to track multiple objects simultaneously across consecutive frames with high accuracy.

- **Customizable Configuration**: Tracify offers customizable configuration options, allowing users to adjust parameters such as confidence thresholds, NMS thresholds, and more to suit their specific requirements.

## Installation

### Prerequisites

Before installing Tracify, ensure you have the following prerequisites installed:

- Python 3.10
- Git
- Requirements specified in requirements.txt
- PyTorch
- Conda

### Installation Steps

1. **Clone the Repository**:

 Clone the Tracify repository to your local machine using Git:
```bash
   git clone https://github.com/AwnishRanjan/Tracify2.0.git
   cd Tracify
   pip install -r requirements.txt

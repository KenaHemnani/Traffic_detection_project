# Traffic Detection Project

###### This project consists of two sub-projects:
       1. Traffic Detection based on traffic images
       2. Traffic Anamoly Detection based on traffic videos

## 1. Traffic Detection

#### Dataset : 

Traffic Detection Dataset: [link](https://www.kaggle.com/datasets/yusufberksardoan/traffic-detection-project?select=data.yaml)

#### Approach : 
In this project we will Benchmark, Compare and Analyze some of the most recent and State of the Art
Object Detection models to be able to choose what suits best for our Traffic Detection Dataset.
Following are the Object Detection models we will explore:
1. YOLOv8
2. YOLOv9
3. YOLOv10

#### Results :

![image](https://github.com/KenaHemnani/Traffic_detection_project/blob/main/traffic_detection_using_images/outputs/comparision_graphs/map_vs_gpu.png)

![image](https://github.com/KenaHemnani/Traffic_detection_project/blob/main/traffic_detection_using_images/outputs/comparision_graphs/mAP_vs_CPU.png)

![image](https://github.com/KenaHemnani/Traffic_detection_project/blob/main/traffic_detection_using_images/outputs/comparision_graphs/mAP_across_all_classes.png)

## 2. Anamoly Detection in Traffic Videos

#### Dataset : 

Detection of Traffic Anomaly
: [DoTA](https://github.com/MoonBlvd/Detection-of-Traffic-Anomaly?tab=readme-ov-file)

#### Approach : 
We will use the pretrained [MOVAD](https://arxiv.org/pdf/2302.10719) model and evaluate the performance on 20 video.
 
MOVAD is built on two primary modules: a Short-Term Memory Module, which extracts
information about ongoing actions using a Video Swin Transformer (VST), and a
Long-Term Memory Module integrated into the classifier, leveraging a Long-Short Term
Memory (LSTM) network to consider past information and action context.

####  Example detection video:

[![Video Thumbnail](https://img.youtube.com/vi/o3xLjjliXOY/0.jpg)](https://youtu.be/o3xLjjliXOY)
# SensAI Kits

This is a collection of context-aware AI kits, fully integrated with the Meta XR SDK and Unity.  
Vision kits are built to support Meta Camera Access (PCA).
<br><br>
<img src="SensAI.gif" width="625" />
<br><br>

## Table of Contents

1. [Zero-Shot Object Detection Kit](#1-zero-shot-object-detection-kit)  
2. [Custom AI Model Training Kit (Roboflow)](#2-custom-ai-model-training-kit-roboflow)  
3. [Text-to-Speech Sample](#3-text-to-speech-sample)  
4. [License](#4-license)  


## Overview


## 1. 🎯 Zero-Shot Object Detection Kit

A Unity plugin that enables real-world object detection in XR using Microsoft Florence-2 on Meta Quest.
<br>
- Instantly detect objects in your environment with zero-shot AI (no training required)  
- Send image data from your Quest to the Florence API and receive rich detection \& description results  
- Fully integrated with Unity for easy setup and flexible use in XR workflows  


### ⚠️ Limitations


- **Not Real-Time:** API response times mean detection is fast but not instantaneous  
- **Requires Internet:** Wi-Fi needed to send images to the cloud API
- **No Timestamps:** Bounding boxes are not time-synced  


#### GitHub: 👉 [Zero-Shot Object Detection Kit](https://github.com/lucas-martinic/Unity-MetaXR-AI-Florence2)  
<br>


## 2. 🤖 Custom AI Model Training Kit (Roboflow)

A Unity plugin that brings you custom-trained object detection to XR — powered by Roboflow and optimized for Meta Quest.
<br>
- Upload and annotate your own image datasets (capturing directly on Meta Quest recommended)  
- Run models locally on-device for faster inference and offline use  
- Fully integrate detection results into your Unity XR app  


### ⚠️ Limitations

- **Setup Time:** Requires effort to collect, annotate, and train datasets  
- **CUDA & Docker Setup Needed:** See [Roboflow’s repo](https://github.com/roboflow/inference)  


#### GitHub: 👉 [Custom AI Model Training Kit](http://github.com/nigelhartm/MetaPCARoboflow)  
<br>

## 3. 🔊 Text-to-Speech Sample
### OpenAI TTS API

- High-quality, natural English voices with low latency  
- Easy API integration and fast setup  
- Free tier includes ~3,000 sentences/month  


#### GitHub: 👉 [XR AI Text to Speech](https://github.com/rikturnbull/xr-ai-text-to-speech)  
<br>

## 4. 📜 License
By downloading and using these kits, you agree to the [License Terms](./LICENSE).

<br>


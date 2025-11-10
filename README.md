# SensAI Kits 🎎

This is a collection of context-aware AI kits, fully integrated with the Meta XR SDK and Unity.  
Vision kits are built to support Meta Camera Access (PCA).

![output-onlinegiftools (1)](https://github.com/user-attachments/assets/61759309-e613-454c-a5c1-4fc4c0aaf1ef)


## 📝 Table of Contents

1. [AI Capabilities Workbench](#1-ai-capabilities-workbench) 
2. [Zero-Shot Object Detection Kit](#2-zero-shot-object-detection-kit)  
3. [Custom AI Model Training Kit (Roboflow)](#3-custom-ai-model-training-kit-roboflow)  
4. [Poker AI Assistant (Roboflow)](#4-poker-ai-assistant-roboflow)  
5. [Relevant Sources & Opportunities](#5-relevant-sources--opportunities)  
6. [License](#6-license)


## Overview

## 1. AI Capabilities Workbench

🎯 A Unity based workbench implementing 7 workflows and 10 providers, to bring contextual AI to your apps. Compatible with Meta Quest.
<br>
- Multi-AI Provider Support – Supports Nvidia, OpenAI, Google Gemini, Groq, Roboflow, Stability AI, and AWS  
- Pre-configured scenes with easy API key management, enabling quick AI-powered XR prototypes 

<br>

:warning: Limitations
* **Requires API Keys:** Users must register with the AI providers and configure their own API keys for detection to work  
* **Requires Internet:** Some of the workflows send calls to cloud API


#### GitHub: 👉 [AI Capabilities Workbench](https://github.com/rikturnbull/xr-ai-workbench) 

<img src="https://github.com/user-attachments/assets/ca964a49-e796-4770-bb2c-70bd92232aa9" alt="AICapabilities" width="540px">

---

## 2. Zero-Shot Object Detection Kit

🎯 A Unity plugin that enables real-world object detection in XR using Microsoft Florence-2 on Meta Quest.
<br>
- Instantly detect objects in your environment with zero-shot AI (no training required)  
- Send image data from your Quest to the Florence API and receive rich detection \& description results  
- Fully integrated with Unity for easy setup and flexible use in XR workflows  

<br>

:warning: Limitations
* **Not Real-Time:** API response times mean detection is fast but not instantaneous  
* **Requires Internet:** Wi-Fi needed to send images to the cloud API
* **No Timestamps:** Bounding boxes are not time-synced  


#### GitHub: 👉 [Zero-Shot Object Detection Kit](https://github.com/lucas-martinic/Unity-MetaXR-AI-Florence2)  

<img src="https://github.com/user-attachments/assets/ba80ee67-4df4-44df-9e82-703a6ceef27f" alt="MetaPCARoboflow" width="540px">

---

## 3. Custom AI Model Training Kit (Roboflow)

🤖 A Unity plugin that brings you custom-trained object detection to XR — powered by Roboflow and optimized for Meta Quest.
<br>
- Upload and annotate your own image datasets (capturing directly on Meta Quest recommended)  
- Run models locally on-device for faster inference and offline use  
- Fully integrate detection results into your Unity XR app  


<br>

:warning: Limitations

- **Setup Time:** Requires effort to collect, annotate, and train datasets  
- **CUDA & Docker Setup Needed:** See [Roboflow’s repo](https://github.com/roboflow/inference)


#### GitHub: 👉 [Custom AI Model Training Kit](http://github.com/nigelhartm/MetaPCARoboflow)  

<img src="https://github.com/user-attachments/assets/5076fbf8-0844-4d00-b9fc-7bdfaa91ab48" alt="MetaPCARoboflow" width="540px">

---

## 4. Poker AI Assistant (Roboflow)

♣️ A Meta Quest application that uses computer vision and Poker Odds API to calculate poker hand strenght in real time. 
<br>
- Detects poker cards and calculates odds and win probabilities
- Runs 100,000+ simulations for highly accurate predictions using the Poker Odds API
- Performs local inference directly on Meta Quest
- Minimalistic UI/UX optimized for wearables 


<br>

:warning: Setup Notes

- **Wi-Fi Configuration:** Ensure Meta Quest is on the same Wi-Fi as your server
- **Server Setup:** Local Roboflow inference server and Node.js Poker Odds server must be running
- **Permissions & IP:** Verify permissions on Meta Quest and correct IP address in RoboflowCaller  
- **CUDA & Docker Setup Needed:** See [Roboflow’s repo](https://github.com/roboflow/inference)  

#### GitHub: 👉 [Poker AI Assistant](https://github.com/nigelhartm/PokerAssistant)  

<img src="https://github.com/user-attachments/assets/c402f050-0691-433a-8fe6-0327efd08412" alt="MetaPCARoboflow" width="540px">

---

## 5. Relevant Sources & Opportunities
* [SensAI Hackademy](https://www.sensaihackademy.com) - Early access program for courses and toolkits
* [SensAI Hack](https://sensaihack.com) - Upcoming hackathons where you can use the kits


---

## 6. License
📜 By downloading and using these kits, you agree to the [License Terms](./LICENSE).

<br>


# 📚 Real-Time Handwritten Digit Recognition Tool

## 📌 Project Overview
Built a **real-time handwritten digit recognition tool** using **AWS SageMaker** and **Streamlit**.  
The project uses a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset** to classify digits 0–9.

## 🏗️ System Architecture
- **AWS SageMaker** for:
  - Data Preprocessing (via Data Wrangler)
  - Model Training (with GPU and hyperparameter tuning)
  - Model Deployment (as a REST API endpoint)
- **Amazon S3** for dataset storage
- **Streamlit** for interactive web interface allowing:
  - ✍️ Draw your digit live
  - 📁 Upload an image file

## ⚙️ Tech Stack
- AWS SageMaker (Training + Deployment)
- Amazon S3
- Streamlit
- PyTorch
- MNIST Dataset

## 🚀 Key Features
- 📈 Achieved **98.79%** test accuracy
- ⚡ Real-time predictions (under 200ms response time)
- 🖌️ Draw or upload digits easily
- 💸 Cost-optimized using AWS Spot Instances (saved ~61%)

## 🧠 Challenges Solved
- **PyTorch Version Issues** ➔ Used custom Docker environments
- **Training Time Costs** ➔ Shifted to managed spot instances

## 🎯 Results
- High model accuracy with low latency
- Deployed fully on cloud with minimal local resource usage
- Simple and intuitive web app for users to interact with the model



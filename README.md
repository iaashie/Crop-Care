# 🌾 Crop Care - Smart Soil Testing System

An IoT and AI-powered solution for real-time soil analysis, providing smart crop and fertilizer recommendations to promote sustainable and precision agriculture.

## 👨‍🌾 Problem Statement

Traditional farming lacks real-time insights into soil health, leading to inefficiencies in resource usage. Farmers need an affordable, accessible system that provides accurate, data-driven recommendations to improve crop yield and soil sustainability.

## 🎯 Our Solution

Crop Care is a real-time IoT-based soil testing system that leverages sensors and AI/ML models to provide actionable recommendations for crop and fertilizer usage.

### ✅ Key Features

- Real-time measurement of soil moisture, pH, temperature, and nutrients (NPK).
- Machine Learning-based soil type identification using camera images.
- Crop and fertilizer recommendation engine trained on 800+ datasets.
- Web dashboard for farmers to visualize results instantly.
- Affordable and scalable for small and marginal farmers.

## 🧰 Tech Stack

- **Hardware**: Raspberry Pi, Soil Moisture Sensor, pH Sensor, NPK Sensor, Camera Module, Wi-Fi Module
- **Software**: Python, Flask, HTML/CSS
- **ML Models**:
  - CNN for soil image classification (1000+ images)
  - Decision Tree / Random Forest for crop & fertilizer recommendation

## 🗂️ System Architecture

```plaintext
[Soil Sensors] ─┬─> [Raspberry Pi] ─> [Web Dashboard]
[Camera Module] ┘      |  
                     [ML Models]

# 🌱 FARM: AI-Based Crop Recommendation App (Frontend)
<p align="center">
  <img src="https://github.com/user-attachments/assets/76ce87e0-460a-481f-a3c0-11595b734708" width="45%"/>
  <img src="https://github.com/user-attachments/assets/de8ae2e1-bc78-4de5-bf37-75efa5c92b15" width="45%"/>
</p>  

<p align="center">
  <img src="https://github.com/user-attachments/assets/13a7d930-d7ea-480f-9e4d-5dfb03972477" width="45%"/>
  <img src="https://github.com/user-attachments/assets/d5e467b6-1062-4dda-9b39-c79731cb4b2e" width="45%"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cfe7e581-4560-40fe-8c78-b459e7c0d930" width="45%"/>
  <img src="https://github.com/user-attachments/assets/8648d66c-6436-4df5-ac40-2ea552f14f22" width="45%"/>
</p>  

**FARM** is an AI-powered mobile application designed to assist farmers in making better crop selection decisions using soil and environmental parameters. It is built with smart agriculture concepts, the application provides crop recommendations through Machine Learning models integrated with a cloud-hosted backend system.

## 🚀 Features

* 🔐 **User Authentication** - Secure login and user registration using Firebase Authentication.

* 🌱 **Soil Data Input** - Users can enter agricultural parameters including Nitrogen (N), Phosphorus (P), Potassium (K), pH value, rainfall, temperature, and humidity.

* 🌦️ **Weather Integration** - Automatically retrieves weather information using Open-Meteo API for more accurate recommendations.

* 🤖 **AI-Based Crop Recommendation** - Uses Machine Learning models to recommend suitable crops based on environmental and soil conditions.

* 🌾 **Fertilizer Recommendation** - Provides fertilizer suggestions to help improve crop growth and soil productivity.

* 📊 **Prediction History** - Stores previous crop recommendations for future reference using Cloud Firestore.

* 📄 **PDF Report Generation & Result Sharing** - Allows users to generate downloadable crop recommendation reports and enables users to share recommendation results.

* 📱 **User-Friendly Interface** - Clean UI for easy accessibility.

* ☁️ **Cloud Backend Integration** - Communicates with a FastAPI backend deployed on Render Cloud.

## 🛠️ Technologies Used

* **Frontend:** Flutter (Dart)
* **Backend Integration:** FastAPI REST API (Python)
* **ML Algorithms:** Random Forest, KNN
* **Weather API:** Open-Meteo API
* **Database & Authentication:** Firebase (Authentication, Cloud Firestore)
* **Backend Deployment:** Render Cloud Platform
* **Code Editor:** Android Studio / VS Code / Google Colab

## 📱 How It Works

1. User logs into the application.
2. The user enters soil parameters and environmental data.
3. Weather information is automatically fetched using GPS.
4. Data is sent to the cloud-hosted backend API.
5. Machine Learning model processes the input data.
6. Predicted crop recommendation is displayed to the user.

## 🎯 Objective

The main goal of **FARM** is to provide farmers with an intelligent and data-driven crop recommendation system that improves agricultural productivity and supports better farming decisions.

## 🔮 Future Enhancements

* 🌐 Multi-language Support
* 📡 IoT Sensor Integration
* 📴 Offline Prediction Capability
* 🤖 Disease Detection Integration

## 📧 Contact
For questions or feedback, please open an issue on GitHub.

----

⭐ If you found this project helpful, please consider giving it a star!

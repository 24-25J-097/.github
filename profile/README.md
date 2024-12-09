# 🏥🩺 Automated Medical Conditions Detection in E.N.T Images Using Deep Learning Techniques

#### [Organization Link](https://github.com/24-25J-097)

## 🌟 Overview

Welcome to the Automated Medical Conditions Detection in E.N.T Images Using Deep Learning Techniques GitHub organization. This organization hosts all code repositories related to our research on the automated identification of ENT-related conditions using advanced deep learning techniques. Our objective is to develop, test, and deploy web and mobile applications for identifying sinusitis, foreign objects in the throat, cholesteatoma in the ear, and pharyngitis in oral images.

### System Diagram
![full-system-diagram](https://github.com/user-attachments/assets/4e92f698-168d-41fd-9546-05b2741bdc72)

## 📁 Repositories

Below, you’ll find a summary of all the repositories within our organization. Each repository has a specific purpose, and together, they form the foundation of our projects.

#### 1. [**ENT Disease Detection DL Models**](https://github.com/24-25J-097/ent-disease-detection-dl-models)

- This repository houses the deep learning models and related APIs for validate images, disease detection and analysis. Each disease module Sinusitis, Cholesteatoma, Pharyngitis and Foreign body detection are implemented using advanced CNN architectures. The FastAPI server provides endpoints for processing uploaded images and returning validity, predictions, severity levels, and classification results.

  - Technologies: Python, FastAPI, Uvicorn, TensorFlow, NumPy, Python Pillow, OpenCV, Roboflow Inference, Python-Multipart, etc.

#### 2. [**ENT Disease Detection Web App**](https://github.com/24-25J-097/ent-disease-detection-webapp)

- This repository is for the web-based interface of the system, which allows doctors and radiologists and medical students to upload medical images, view results, and access reports. The application provides a user-friendly interface for interacting with the Node.js API and displaying disease prediction outputs fetched from the FastAPI server.

  - Technologies: Next.js, React, TypeScript, Axios, Tailwind CSS, etc.

#### 3. [**ENT Disease Detection Mobile App**](https://github.com/24-25J-097/ent-disease-detection-mobile-app)

- This repository manages the mobile application designed for Android and iOS platforms. It enables doctors and radiologists and medical students to upload images, view diagnosis reports, and access notifications on the go. The app ensures seamless communication with the Node.js API for data transmission and the FastAPI server for results retrieval.

  - Technologies: Flutter, Dart, Firebase, etc.

#### 4. [**ENT Disease Detection API**](https://github.com/24-25J-097/ent-disease-detection-api)

- This repository contains the backend logic for managing user authentication, report generation, and notification services. It acts as the main communication hub between the Web/Mobile applications and the FastAPI server. This Node.js based REST API handles incoming requests, validates them, and routes data to the appropriate deep learning modules or services in the FastAPI server. The API also incorporates MongoDB as the primary database for storing and managing critical data.

  - Technologies: Node.js, Express.js, TypeScript, Passport.js, MongoDB, Axios, etc.

## 🚀 Project Goals

1. Quick, Accurate Diagnoses: Provide automated, high-accuracy solutions for detecting sinusitis, foreign throat objects, cholesteatoma, and pharyngitis.
2. Severity Classification: Implement models to classify severity stages of sinusitis and pharyngitis.
3. User-Friendly Access: Design web and mobile applications that integrate seamlessly into clinical workflows.

## 🛠️ Getting Started

Each repository contains a detailed `README.md` with setup instructions, requirements, and usage notes. Please refer to individual repositories for more information on deployment and testing.

## 📜 License

Copyright (c) 2024 24-25J-097

All rights reserved. No part of this software may be reproduced, distributed,
or transmitted in any form or by any means, including photocopying, recording,
or other electronic or mechanical methods, without prior written permission
from the author, except in the case of brief quotations in reviews or academic use.

Unauthorized use, modification, or distribution is prohibited.

## 🤝 Contact Us

Have questions?

- Email: [it21156410@my.sliit.lk](mailto:it21156410@my.sliit.lk) / [it21169908@my.sliit.lk](mailto:it21169908@my.sliit.lk) / [it21156038@my.sliit.lk](mailto:it21156038@my.sliit.lk) / [it21247804@my.sliit.lk](mailto:it21247804@my.sliit.lk)

# AI Projects Hub

Hi there, I'm **Raafat Nagy**, an AI Engineer focused on building intelligent systems across Computer Vision, Machine Learning, Deep Learning, Time-Series Forecasting, and NLP / RAG.\
This repository serves as a central hub for my AI projects in these domains, covering both model development and end-to-end system design.

<div align="center">
    <a href="https://www.linkedin.com/in/raafat-nagy/"><img src="https://img.shields.io/badge/LinkedIn-Raafat--Nagy-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/Raafat-Nagy"><img src="https://img.shields.io/badge/GitHub-Raafat--Nagy-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="mailto:RaafatNagy89@gmail.com"><img src="https://img.shields.io/badge/Contact-Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

## Table of Contents

- [Computer Vision Projects](#computer-vision-projects)  
- [Deep Learning Projects](#deep-learning-projects)  
- [Machine Learning Projects](#machine-learning-projects)  
- [Time Series and Forecasting Projects](#time-series-and-forecasting-projects)  
- [Future Work](#future-work)  

---

## Computer Vision Projects  

1. **Vehicle Detection, Tracking, Counting and Speed Estimation**  
   - Developed a real-time traffic monitoring system using **YOLO** and **ByteTrack**.  
   - Implemented speed estimation with perspective transformation for accurate measurements.  
   - Supported configurable counting zones and custom YOLO models.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Vehicle-Speed-Estimation-and-Counting-YOLO-Supervision) &nbsp;-&nbsp; [Demo Video](https://youtu.be/1HSTwBKCELk)  

2. **YOLO Object Detection App**  
   - Built a real-time object detection web app with **FastAPI backend** and **JavaScript frontend**.  
   - Features drag & drop uploads, multiple model options, smart video streaming, and dark mode UI.  
   - Integrated advanced CV models with smooth asynchronous processing.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/YOLO-Object-Detection-App) &nbsp;-&nbsp; [Demo Video](https://youtu.be/ONM9z99RVaU)  

3. **Smart Face Attendance System**  
   - Created a real-time face recognition attendance system using **OpenCV** and **face_recognition**.  
   - Automated attendance logging with webcam detection and CSV export.  
   - Optional API integration for backend synchronization.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/SmartFace_Attendance_System)  

4. **Student Entry and Exit Tracking**  
   - Developed a system for tracking and counting students entering/exiting halls using **YOLO** and **OpenCV**.  
   - Used **Shapely** for zone-based direction detection.  
   - Enabled CSV logging and API reporting.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Real_Time_Student_Entry_and_Exit_Tracking_via_Computer_Vision)  

5. **Facial Landmark and Drowsiness Detection**  
   - Implemented real-time facial landmark detection and drowsiness monitoring using the **EAR method**.  
   - Built with **OpenCV** and **dlib** for accurate fatigue alerts.  
   - Enhanced driver and workplace safety.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Facial-Landmark-and-Drowsiness-Detection) &nbsp;-&nbsp; [Demo Video](https://youtu.be/aCKkCBUu3DM)  

6. **Object Detection Telegram Bot**  
   - Developed asynchronous Telegram bot for real-time object detection on user-submitted images.  
   - Automated annotation and detailed detection summaries.  
   - Built with **OpenCV** and **python-telegram-bot** for efficient performance.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Object-Detection-Telegram-Bot) &nbsp;-&nbsp; [Demo Video](https://youtu.be/0K8c3HZsd2U)  

---

## Deep Learning Projects  

All projects are included in [Deep Learning Projects repository](https://github.com/Raafat-Nagy/Deep-Learning-Projects):

1. **Brain Tumor MRI Classification**  
   - Developed a model using **TensorFlow** and **ResNet50V2** for brain tumor detection from MRI images.  
   - Improved performance via data augmentation and transfer learning.  
   - Evaluated with confusion matrix and classification reports.  

2. **Oral Diseases Classification**  
   - Built a multi-class classification model to identify six oral diseases using **TensorFlow** and **ResNet50V2**.  
   - Applied preprocessing, augmentation, and fine-tuned pre-trained layers.  
   - Assessed accuracy with detailed reports and confusion matrices.  

3. **Plant Disease Detection**  
   - Designed a CNN to classify 38 plant disease categories with **TensorFlow/Keras**.  
   - Used batch normalization and dropout for better generalization.  
   - Achieved high validation accuracy through image augmentation.  

4. **MNIST Handwritten Digit Classification**  
   - Created CNN for 10-class digit classification on grayscale images using **TensorFlow**.  
   - Applied data augmentation, dropout, early stopping, and learning rate scheduling.  
   - Validated with accuracy metrics and prediction visualizations.  

5. **Autoencoder Projects on MNIST**  
   - Developed convolutional, simple, and denoising autoencoders for image compression and noise removal.  
   - Used convolution, max-pooling, and upsampling layers in encoder-decoder architecture.  
   - Evaluated reconstruction quality by comparing original and reconstructed images.  

---

## Machine Learning Projects  

1. **Machine Learning From Scratch**  
   - Developed fundamental ML algorithms (Linear Regression, Logistic Regression, SVM, Decision Trees, KNN, Clustering, PCA) from scratch in Python.  
   - Emphasized mathematical understanding and clean, well-documented code for educational use.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Machine-Learning-From-Scratch)  

2. **Diabetes Prediction Project**  
   - Built ML models for diabetes prediction using patient health data with **Python** and **scikit-learn**.  
   - Conducted data exploration, visualization, feature engineering, and hyperparameter tuning.  
   - Deployed an interactive **Streamlit app** for real-time risk prediction.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Diabetes_Prediction_Project) &nbsp;-&nbsp; [Streamlit App](https://diabetes-prediction--project.streamlit.app/)  

3. **Iris Flower Species Prediction**  
   - Created an **SVM** model to classify Iris species based on sepal and petal measurements.  
   - Performed data preprocessing and exploratory analysis.  
   - Developed a **Streamlit web app** for user-friendly species prediction with dynamic visualization.  
   - [GitHub Repo](https://github.com/Raafat-Nagy/IRIS-Project) &nbsp;-&nbsp; [Streamlit App](https://iris-flowers-prediction.streamlit.app/)  

---

## Time Series and Forecasting Projects  

1. **Bitcoin Price Forecasting System**  
   - Built an end-to-end time-series forecasting system for Bitcoin price prediction.  
   - Implemented multiple models including Prophet, ARIMA, and Auto-ARIMA with full evaluation pipeline.  
   - Developed an interactive Streamlit dashboard for forecasting, visualization, and uncertainty analysis.  
   - Handled financial time-series challenges such as volatility, missing data, and backtesting.  
   - Structured with a modular architecture (data processing, modeling, and UI layers).  
   - [GitHub Repo](https://github.com/Raafat-Nagy/Bitcoin-Forecasting-App) &nbsp;-&nbsp; [Streamlit App](https://bitcoin-forecasting-app.streamlit.app)  


---

## Future Work  

This repository will continue to be updated with new projects and research work in the areas of:  
- Machine Learning  
- Deep Learning  
- Computer Vision  
- AI Systems Integration

# Land Zoning Using Satellite Imagery and Machine Learning

## 📷 Tools Utilized

<table>
  <tr>
    <td align="center"><img src="Images/python-logo.png" width="100"></td>
    <td align="center"><img src="Images/tensorflow.png" width="100"></td>
  </tr>
  <tr>
    <td align="center"><strong>Python</strong></td>
    <td align="center"><strong>TensorFlow</strong></td>
  </tr>
</table>
            
 

## 📌 Project Overview
This project focuses on developing a comprehensive system for **land zoning** using **satellite imagery** and **machine learning** techniques. The primary objective is to classify land areas based on their suitability for **barren land, water, and vegetation**. The approach involves advanced image processing and **Neural Network (NN)-based classification** to enhance land analysis accuracy, aiding in **data-driven land use planning** and **resource management**.

This project extends ongoing research work, which has been recognized and accepted by multiple international journal institutions for its innovative approach to land classification using satellite imagery and machine learning.

## 🚀 Key Highlights
- **Technology Stack**: TensorFlow, Python, Sentinel Hub, Kaggle Open-Source Dataset, OpenCV, Rasterio, NumPy, Matplotlib
- **Model Type**: Neural Network (NN) for multi-class classification
- **Methodology**: Data Acquisition → Preprocessing → Classification → Scoring → Visualization

## 📥 Data Collection
Satellite images are collected from:
- **Sentinel Hub**: Offers real-time satellite imagery.
- **Kaggle Open-Source Dataset**: A publicly available dataset used for training and evaluation. [Click here to access the dataset](https://www.kaggle.com/datasets/requiemonk/sentinel12-image-pairs-segregated-by-terrain) and  [Click here to access the dataset](https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies).

## 🛠 Data Preprocessing
The images were processed through the following steps:
- Extracted from respective file directories based on **barren land, water, and vegetation** classification.
- Resized to a uniform **256x256** pixel dimension for consistent input to the model.

## 🏗 Model Development
A **Neural Network (NN)** was developed using **TensorFlow**:
- Trained on **labeled images** with **data augmentation** for better accuracy.
- Uses **Neural Networks** for feature extraction.
- **Evaluation Metrics**: Accuracy, Loss Function Calculation.

## 📊 Scoring & Visualization
Each image is **scored on a scale of 0 to 1** for land suitability:
- **Barren Land**: Identified through surface texture analysis.
- **Vegetation**: Classified based on greenery levels.
- **Water**: Detected through edge analysis and color differentiation.

## 📑 Reporting
The final output includes:
- **Classified land maps** with **metric scores**.
- **Graphs & distribution plots** for visualization.
- **Comprehensive report** summarizing methodology, findings, and land use recommendations.

## 📚 Skills Demonstrated
✅ **Machine Learning & Deep Learning**: TensorFlow-based model training.  
✅ **Data Processing**: Image segmentation, classification, and preprocessing.  
✅ **Visualization**: Graphs, heatmaps, and suitability scores.  
✅ **Project Management**: End-to-end ML pipeline implementation.

## ⚡ Future Enhancements
- Integrate **time-series analysis** for land use change detection.
- Deploy as a **web application** for real-time land assessment.
- Optimize the model with **Transfer Learning** for improved classification.

---

## 📜 License
This project is open-source under the **MIT License**.

## 🤝 Contributing
We welcome contributions! Feel free to open issues and submit PRs.

## 📬 Contact
For queries, reach out via **[LinkedIn](https://www.linkedin.com/in/suryavardhan8)** or through mail - **suryavardhankarella@gmail.com**.

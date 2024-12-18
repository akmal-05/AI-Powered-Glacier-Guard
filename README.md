# 🌍 Glacier Guard: Monitoring and Detecting Glacier Changes Using YOLOv8 
 

## 🚀 Abstract

Glacier Guard is a deep learning-based object detection system designed to monitor glacier changes using YOLOv8. The project focuses on detecting lake formation, glacier retreat, and water runoff using satellite imagery. A custom dataset of 208 images of the Badswat Glacier (2013–2024) was curated and augmented to 580 images for training. With promising results (mAP of 0.83), Glacier Guard demonstrates the feasibility of leveraging deep learning for glacier monitoring and early warning systems. Future work aims to expand coverage across Gilgit-Baltistan and enable real-time deployment.


## 📂 Key Features
1)  📸 Object Detection: Identifies critical features in glacier images:
- Lake Formation
- Glacier Retreat Areas
- Water Runoff
2) 🛰️ Custom Dataset:
- Time-stamped images of Badswat Glacier (2013–2024).
- Dataset augmented for improved model generalization.
3) 📊 Performance:
- Precision: 0.903
- Recall: 0.781
- mAP: 0.83
- F1 Score: 0.838
4) 🌐 Real-World Applications:
- Early warning systems for glacier lake outburst floods (GLOFs).
- Monitoring climate change effects on glaciers.

## Dataset
1. Data Collection
- Source: Google Earth Pro satellite images.
- Location: Badswat Glacier, Gilgit-Baltistan.
- Time Span: 2013 to 2024
- Total Images: 208
2. Data Augmentation
- Flipping: Horizontal and vertical flips.
- Rotation: Random rotations between ±15°.
- Saturation: Simulating diverse lighting conditions.
Final Dataset: 580 Images


## Methodology
1. Model Architecture
- YOLOv8: Selected for its speed and accuracy in real-time object detection tasks.
2. Training Configuration
- Epochs: 50
- Batch Size: 16
- Image Size: 224x224
- Learning Rate: 0.01
3. Classes:
- Lake Formation
- Retreat Area
- Water Runoff
4. Validation
- Validation Set: 21 Images
- Metrics: Precision, Recall, mAP, and F1 Score.
5. Results
The YOLOv8 model achieved:
- ✅ Precision: 0.903
- ✅ Recall: 0.781
- ✅ mAP: 0.83
- ✅ F1 Score: 0.838


##  Future Work
🚀 Next Steps for Glacier Guard:

- Expand the dataset to include other glaciers in Gilgit-Baltistan.
- Integrate time-series analysis for temporal monitoring.
- Deploy the model for real-time alerts and monitoring systems.

## References
- Redmon, J., et al. (2016). You Only Look Once: Unified, Real-Time Object Detection.
- Google Earth Pro. Satellite Imagery Dataset.
- Ultralytics. (2024). YOLOv8 Documentation.

## Contact
- 👤 Akmal Ali
- 📧 Email: akmal.aleee@email.com
- 🔗 LinkedIn: https://www.linkedin.com/in/akmal-ali-218322258/





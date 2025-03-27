# 🚀 Social Proximity and Mask Monitoring System  
## 📌 Overview  
The **Social Proximity and Mask Monitoring System** is an AI-powered solution that detects **social distancing violations** and **mask adherence** using **computer vision and IoT**. It processes real-time video feeds to monitor compliance and provides instant alerts to ensure public safety.  

## 🚀 Getting Started  
Follow the steps below to download, set up, and run the project on your local machine.  


# 1️⃣ Prerequisites  
# Ensure you have the following installed:  
- Python 3.8+  
- pip (latest version)  
- OpenCV & TensorFlow for computer vision  
- YOLOv3 or MobileNet (pre-trained model for mask detection)  
- Raspberry Pi (optional for IoT integration)  

# 2️⃣ Clone the Repository  
git clone https://github.com/your-username/repo-name.git  
cd repo-name  

# 3️⃣ Install Dependencies  
pip install -r requirements.txt  

# 4️⃣ Dataset Preparation  
The system uses an image/video dataset containing mask-wearing individuals and social distancing scenarios.  
If using a custom dataset, store images in the `data/` directory.  
Example CSV format:  
image_path,mask_label,distance_violated  
"data/img1.jpg", "No Mask", "Yes"  
"data/img2.jpg", "Masked", "No"  

# 5️⃣ Run the Detection Model  
python detect.py --source video.mp4  
The system will process live feeds or recorded videos and display alerts.  

# 6️⃣ Deploy as an API (Optional)  
To serve the model using Flask/FastAPI, run:  
python app.py  
Then open your browser and go to:  
http://127.0.0.1:5000/predict?image=your_image.jpg  

# 🎯 Features  
✔️ Real-time mask detection using AI models  
✔️ Social distancing monitoring using computer vision  
✔️ Works with live CCTV feeds or recorded videos  
✔️ Can be deployed on IoT devices (Raspberry Pi, Jetson Nano)  
✔️ API support for easy integration into applications  

# 🤝 Contributing  
# Want to contribute? Follow these steps:  
1. Fork the repository  
2. Create a new branch:  
git checkout -b feature-branch  
3. Commit your changes:  
git commit -m "Added new feature"  
4. Push the branch:  
git push origin feature-branch  
5. Open a Pull Request on GitHub  

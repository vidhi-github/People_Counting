# **People Counting System using Computer Vision**  

## **Overview**  
The **People Counting System** is a computer vision-based application designed to detect, track, and count people entering or exiting a specific area in real-time. This system uses deep learning models and object detection techniques to provide accurate, real-time data. It leverages AI technologies like YOLOv8, MTCNN, and OpenCV, making it suitable for various real-world applications such as occupancy monitoring and crowd management.  

---

## **Key Features**  
- 🚶 Real-time detection and tracking of people.  
- 📈 Accurate counting of individuals moving in different directions.  
- 🏃 Person detection using YOLOv8 and MTCNN models.  
- 🎥 Frame-wise processing using OpenCV.  
- ⚡ GPU acceleration with CUDA for faster inference.  
- 🌐 Flask-based web interface for real-time result visualization.  

---

## **Technologies Used**  
- **Python 3.12+**: Core programming language.  
- **OpenCV**: Real-time video and image processing.  
- **TensorFlow**: Deep learning framework for object detection.  
- **MTCNN**: For face detection and tracking.  
- **YOLOv8**: Object detection model for identifying people.  
- **NumPy & Pandas**: Data handling and manipulation.  
- **Flask**: Web interface for real-time monitoring.  

---

## **Data Annotation**  
- **Annotation Tool:** `cv2` library for frame-based annotation.  
- **Format:** JSON.  
- **Process:**  
  - Extract frames from videos.  
  - Annotate bounding boxes around each detected person.  
  - Save annotations for model training and validation.  

---

## **Project Setup**  

### 🔄 **1. Clone the Repository**  
```bash
git clone https://github.com/your-repository/people-counting-system.git
cd people-counting-system
```  

### 💾 **2. Set Up the Environment**  
```bash
sudo apt update
sudo apt install python3.8-venv
python -m venv newenv
source newenv/bin/activate
```  

### 📦 **3. Install Dependencies**  
```bash
pip install -r requirements.txt
```  

### 🚀 **4. Run the System**  
```bash
python3 app.py
```  

---

## **Deployment on NVIDIA DGX Server**  

### 🌐 **1. Access the DGX Server:**  
Navigate to the DGX server's IP address in your web browser:  
```plaintext
http://<DGX_IP_address>:<application_port>
```  

### 📂 **2. Transfer Files to DGX Server:**  
```bash
scp -r -P <port_number> <local_folder> user@<DGX_IP>:<remote_folder>
```  

### 🎬 **3. Execute the Application:**  
```bash
python3 app.py
```  

---

## **Real-Time Output**  
- The system displays live video streams with bounding boxes around detected individuals.  
- Counts of people moving **up** and **down** are displayed on the interface in real time.  

---

## **Conclusion**  
The **People Counting System** demonstrates the practical application of deep learning and computer vision techniques to track and count individuals in real-time. This project provided hands-on experience in deploying scalable AI solutions with GPU acceleration using NVIDIA DGX systems.  

---

✨ **Built by:** *Vidhi Jindal*  
💡 *Thanks for exploring this project. Happy Learning!*  

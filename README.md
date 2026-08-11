# university-final-project
Object detection, depth mapping, and nearest person identification using YOLOv8 &amp; Depth Anything

# 🧠 Object Detection & Depth Estimation System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![YOLOv8](https://img.shields.io/badge/YOLO-v8-green.svg)
![Depth Anything](https://img.shields.io/badge/Depth-Anything-orange.svg)


## 📌 Project Description

This project combines two powerful deep learning models to analyze images comprehensively:
- **YOLOv8** for real-time object detection
- **Depth Anything** for monocular depth estimation

The system detects objects in an image, generates a depth map, and identifies the **closest person** to the camera by combining the outputs of both models. A user-friendly GUI built with Tkinter makes it easy for anyone to use.

---

## 🎯 Key Features

- ✅ **Object Detection** – Detect and classify objects using YOLOv8
- ✅ **Depth Estimation** – Generate depth maps using Depth Anything
- ✅ **Closest Person Identification** – Find the nearest person based on depth information
- ✅ **Class Selection** – Choose specific classes (Person, Car, Cat, Dog) or detect all objects
- ✅ **Graphical User Interface** – Intuitive Tkinter-based interface
- ✅ **Automatic Result Saving** – Save detection results, depth maps, and final images
- ✅ **GPU/CPU Support** – Automatically uses GPU if available, otherwise runs on CPU

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.8+ | Programming language |
| YOLOv8 (Ultralytics) | Object detection |
| Depth Anything (Hugging Face) | Depth estimation |
| OpenCV | Image processing & visualization |
| Tkinter | GUI development |
| PyTorch | Deep learning backend |
| NumPy | Numerical operations |

---

## 📦 Project Structure

```
YOLO_Depth_Project/
│
├── main.py                 # Main application code
├── README.md               # Project documentation
│
├── results/                # Output images folder (auto-created)
│   ├── 1_yolo_detection.png
│   ├── 1_depth_map.png
│   └── 1_final_result.png
│
└── .gitignore              # Git ignore file
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/saba-roshani/YOLO_Depth_Project.git
cd YOLO_Depth_Project
```

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Download Model Weights

The code automatically downloads the required models:
- **YOLOv8n** (~6 MB)
- **Depth Anything Small** (~1 GB)

> **Note:** The first run may take a few minutes to download the models.

### 4️⃣ Run the Application

```bash
python main.py
```

---

## 📖 How to Use

1. **Select Image** – Click "Select Image" and choose an image from your computer
2. **Choose Class** – Select a specific class (Person, Car, Cat, Dog) or "All Objects"
3. **Start Processing** – Click the "Start Processing" button
4. **View Results** – The results will appear in:
   - The GUI text area (statistics and summary)
   - A separate window showing three images side by side:
     - YOLO Detection Results
     - Depth Map
     - Final Result with Closest Person Highlighted

### Example Output

| Detection Result | Depth Map | Final Result |
|------------------|-----------|--------------|
| Objects detected with bounding boxes | Color-coded depth map | Closest person highlighted in red |

---

## 🔒 Access & Security

This repository contains the **encrypted source code** of the project.

- **File:** `YOLO_Depth_Project.zip`
- **Password:** `SRosha@YoloProject`

To access the source code, extract the ZIP file using the password above.

> ⚠️ **Important:** The password is provided here for the instructor's access. Do not share it publicly.


---

## 📈 Performance

| Model | Average Time |
|-------|-------------|
| YOLOv8 Detection | ~0.3 seconds |
| Depth Anything Estimation | ~0.5 seconds |
| Total Processing | ~0.8 seconds |

> **Note:** Times may vary based on hardware and image resolution.

---

## ⚠️ Limitations

1. **Small Objects** – Very small or distant objects may not be detected
2. **Similar Classes** – Confusion between similar classes (e.g., cat vs. dog)
3. **Crowded Scenes** – Detection accuracy decreases in highly crowded images
4. **Relative Depth** – Depth is relative, not absolute (in meters)
5. **Person-Only** – Closest object detection only works for people

---

## 👩‍💻 Author

**Saba Roshani**  
Student ID: 40211541054026  
Islamic Azad University, Karaj Branch  
Faculty of Artificial Intelligence

---

## 📚 References

- Ultralytics. (2024). YOLOv8 Documentation.  
- Hugging Face. (2024). Depth Anything Model.  
- PyTorch Documentation. (2024).  
- OpenCV Documentation. (2024).

---

## 📄 License

This project is for educational purposes only and is not intended for commercial use.

---

**Thank you for reviewing my project! 🙏**

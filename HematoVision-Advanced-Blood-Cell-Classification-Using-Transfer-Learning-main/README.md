
---

## 🧬 HematoVision – AI-Based Blood Cell Image Classifier

**HematoVision** is a lightweight, intelligent web application designed to classify blood cells using deep learning techniques. It empowers medical practitioners, lab technicians, and researchers with quick diagnostics by analyzing microscopic images of blood samples.

---

### 🎯 Mission

Enable fast, AI-assisted detection of white blood cell types from images to support blood-related diagnostics and research.

---



## 📸 How It Works

🖼️ Users upload an image of a white blood cell.

🤖 The AI model (based on MobileNetV2 and TensorFlow) classifies the cell as one of:

* **Eosinophil**
* **Lymphocyte**
* **Monocyte**
* **Neutrophil**

✅ The model returns an **instant prediction** along with the displayed image, enabling rapid analysis.

---

## ⚙️ Technologies Used

| Component          | Technology            |
| ------------------ | --------------------- |
| Programming        | Python                |
| Backend            | Flask (Web Framework) |
| AI/ML Framework    | TensorFlow (Keras)    |
| Model Architecture | MobileNetV2           |
| Frontend           | HTML, CSS             |
| Image Handling     | OpenCV                |

---

## 🌟 Benefits

* 🔍 **Accurate White Blood Cell Classification** – Helps in disease diagnostics and analysis
* ⚡ **Fast & Lightweight** – Instant prediction on uploaded image
* 💰 **Cost-Effective** – Works without advanced lab infrastructure
* 🧪 **Research Support Tool** – Aids in research and early-stage investigation
* 🧠 **Medical-AI Showcase** – Combines deep learning with healthcare innovation

---

## 🧠 Project Structure

```
blood_cell_classifier/
├── app.py                  # Main Flask application
├── utils.py                # Image preprocessing and prediction logic
├── Blood_Cell.h5           # Pre-trained deep learning model
├── static/                 # CSS, images (optional)
├── templates/              # HTML files: home.html, result.html
│   ├── home.html
│   └── result.html
├── requirements.txt        # Python dependencies
├── .gitignore              # Ignore unnecessary files
└── README.md               # Project overview
```

---

## 🚀 Getting Started

### 📦 Clone the Repository

```bash
git clone https://github.com/your-username/Blood_Cell_Classifier.git
cd Blood_Cell_Classifier
```

### 🔧 Install Dependencies

```bash
python3 -m venv venv
source venv/bin/activate        # For Linux/macOS
venv\Scripts\activate           # For Windows

pip install -r requirements.txt
```

### 📁 Model Setup

Ensure the model file `Blood_Cell.h5` is placed in the project root.
*No download needed — it's already included in the repo.*

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and navigate to: [http://localhost:5000](http://localhost:5000)

---

## 👥 Team Members

| Name                      | Role           |
| ------------------------- | -------------- |
| C Yateesh Kumar           | UI Design & Testing |
| Bhupathi Aasritha         |  Data Preparation   |
|  Boreddy Likithai         |  Documentation  |
| Boya Rajesh               | Backend Developer  |

---

## 📫 Contact

📧 **Email:** Rajesh.Pro.8341@Gmail.Com**
📍 **Location:** Andhra Pradesh, India

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use and adapt.

---

## 🙏 Acknowledgements

* TensorFlow & Keras for the deep learning backend
* OpenCV for image processing
* Flask for easy web app development
* The medical datasets and community for inspiring this tool

---



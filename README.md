# 🏥 RetinaVision AI – Retinal Disease Detection using Deep Learning  

🔬 **RetinaVision AI** is an advanced deep learning model that detects retinal diseases from Optical Coherence Tomography (OCT) images. Using a fine-tuned **DenseNet-121** model, this app can classify retinal scans into **five categories**:  

![Example OCT Image](https://upload.wikimedia.org/wikipedia/commons/9/9f/SD-OCT_Macula_Cross-Section.png)
The healthy macula of a 24 year old male (cross-section view). This image is released to Wikimedia with patient consent. Imaged in-vivo with an Optovue iVue Spectral Domain Optical Coherence Tomographer (SD-OCT) at the office of Drs. Harry Wiessner, Steven Davis, Daniel Wiessner, and Eric Wiessner in Walla Walla, WA, USA.

Web App: [RetinaVision AI](https://retinavisionai.streamlit.app/)
✅ **Normal**  
🩸 **Diabetic Retinopathy**  
👁️ **Age-related Macular Degeneration (AMD)**  
⚠️ **Glaucoma**  
🌫️ **Cataract**  

---

## 🚀 Features  
✔ **Deep Learning-based Disease Detection** using **DenseNet-121**  
✔ **User-friendly Web App** built with **Streamlit**  
✔ **Upload & Analyze** multiple OCT images instantly  
✔ **Real-time Predictions** with confidence scores  
✔ **Supports 5 Retina Conditions** for accurate diagnosis  

---

## 📂 Dataset Structure  
Ensure your dataset follows this structure:  

```
dataset/
│── train/
│   ├── normal/
│   ├── diabetic_retinopathy/
│   ├── amd/
│   ├── glaucoma/
│   ├── cataract/
│
│── val/
│   ├── normal/
│   ├── diabetic_retinopathy/
│   ├── amd/
│   ├── glaucoma/
│   ├── cataract/
│
│── test/
│   ├── normal/
│   ├── diabetic_retinopathy/
│   ├── amd/
│   ├── glaucoma/
│   ├── cataract/
```

📌 **Each folder should contain images of the respective class.**

---

## 🛠️ Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/RetinaVision-AI.git
cd RetinaVision-AI
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App  
```bash
streamlit run app.py
```

---

## 📊 Model Training  
To train the model on your dataset, run:  
```bash
python train.py
```

---

## 🖼️ Sample Predictions  
Upload an OCT image, and the model will predict:  
🔍 **Category** (e.g., Normal, Diabetic Retinopathy, etc.)  
📊 **Confidence Score (%)**  

---

## 💡 Technologies Used  
🔹 **Python** 🐍  
🔹 **PyTorch** 🔥  
🔹 **Torchvision** 🖼️  
🔹 **Streamlit** 🎨  
🔹 **Pandas** 📊  
🔹 **PIL (Pillow)** 🖼️  

---

## 🤝 Contributing  
Want to improve RetinaVision AI? Feel free to contribute!  

### 1️⃣ Fork this repository 🍴  
### 2️⃣ Create a new branch 🏗  
### 3️⃣ Make your changes and commit them 💾  
### 4️⃣ Submit a Pull Request 🔄  

---

## 🏅 Acknowledgements  
🙌 Thanks to **OpenAI, PyTorch, and the AI community** for continuous support!  

---

## 📞 Contact  
💌 Email: your-email@example.com  
🔗 LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)  
🐙 GitHub: [Your GitHub](https://github.com/yourusername)  

---

## 📜 License  
📄 This project is **open-source** under the MIT License.  

🚀 **Let's revolutionize eye health with AI!** 🏥👁️💡  

---

📌 **Replace `yourusername`, `your-email@example.com`, and links with your actual details before uploading.**  

Let me know if you need modifications! 🚀🔥

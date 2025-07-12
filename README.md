# 🌾 GrowGuide - Crop Recommendation System using Machine Learning  

## 📌 Overview  
The **GrowGuide** is a machine learning-based web application that suggests the most suitable crop for cultivation based on **soil conditions, environmental factors, and nutrient levels**. The system uses **Flask** for backend, **Jupyter Notebook** for training models, and a **CSV dataset** for analysis.  

## 🚀 Features  
✅ Machine learning models for crop prediction  
✅ Flask-based API for model deployment  
✅ User-friendly web interface  
✅ CSV dataset with soil & climate data  
✅ Supports **Decision Tree, Random Forest, SVM, and Gradient Boosting**  

---

## 🛠️ Tech Stack  

| Technology  | Purpose |
|-------------|---------|
| **Python** | Core programming language |
| **Flask** | Backend API development |
| **Jupyter Notebook** | Model training and evaluation |
| **Pandas & NumPy** | Data processing |
| **Scikit-learn** | Machine learning models |
| **Matplotlib & Seaborn** | Data visualization |
| **HTML, CSS, JavaScript** | Frontend UI |
| **CSV Dataset** | Crop & soil data |

---

## ScreenShot
<img width="1920" height="1080" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/cb7b02dc-2233-45f1-b3ae-f4ac19cdb6d0" />
<img width="1920" height="1080" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/931bc132-c9a5-48f0-b54b-cf04179e5a5b" />


---

## 📂 Project Structure  

📁 Crop-Recommendation-System │── 📂 dataset │ └── crop_data.csv │── 📂 notebooks │ ├── data_preprocessing.ipynb │ ├── model_training.ipynb │ └── model_evaluation.ipynb │── 📂 backend │ ├── app.py │ ├── model.pkl │ └── requirements.txt │── 📂 frontend │ ├── static │ ├── templates │ └── index.html │── README.md └── .gitignore

yaml
Copy
Edit

---

## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
- git clone https://github.com/yourusername/Crop-Recommendation-System.git
- cd Crop-Recommendation-System

### 2️⃣ Install Dependencies

- pip install -r requirements.txt

### 3️⃣ Run Jupyter Notebook
- jupyter notebook
- Open notebooks/model_training.ipynb and run the cells to train the model.
- Save the trained model as model.pkl.

### 4️⃣ Run Flask Backend
- cd backend
- python app.py
- Flask server starts at http://127.0.0.1:5000/.
- 📊 Dataset Details
- The dataset (crop_data.csv) contains soil and environmental features like:

- N, P, K (Nitrogen, Phosphorus, Potassium)
- Temperature & Humidity
- pH Level
- Rainfall
- Crop Label
### 🎯 Model Performance
- Model	Accuracy
- Decision Tree	92%
- Random Forest	96%
- SVM	88%
- Gradient Boosting	94%

### 💡 Future Enhancements
- 🔹 Integrate real-time weather data
- 🔹 Add market price analysis for crops
- 🔹 Develop a mobile app version
- 🔹 Enhance UI/UX with interactive visuals

### 📝 Contributing
- Feel free to fork this repository and contribute!

- Fork the repo
- Create a new branch
- Commit your changes
- Push & submit a PR

### 📜 License
- This project is open-source and available under the MIT License.

### 📧 Contact
- 🔹 Author: Ayush Yadav 
- 🔹 Email: 2k22.cse.2213307@gmail.com
- 🔹 LinkedIn: https://www.linkedin.com/in/ayush-yadav-143536253/

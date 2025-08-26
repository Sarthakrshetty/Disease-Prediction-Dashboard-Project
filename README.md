 Disease Prediction Dashboard  

🚀 A Machine Learning powered web application to predict the likelihood of diabetes based on user health parameters.  
The project uses Random Forest Classifier for prediction and is deployed with Flask and a professional interactive dashboard UI.  



 Features  

User-friendly web dashboard with modern design  
Predicts disease probability (Diabetes) using ML model  
Displays prediction confidence (%)  
Interactive charts and professional styling  
Built with Python (Flask, Scikit-learn, Pandas)  



 Project Structure  
 DiseasePrediction/
│
├── app.py # Flask backend
├── train_model.py # ML model training script
├── model.pkl # Trained ML model
├── requirements.txt # Dependencies
├── static/ # CSS, JS, images
│ └── style.css
├── templates/ # HTML files
│ └── index.html
└── README.md # Project documentation




Installation & Setup :
Clone the Repository  

bash
git clone https://github.com/YOUR_USERNAME/DiseasePrediction.git
cd DiseasePrediction


2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Train the Model (Optional if model.pkl exists)
python train_model.py


4️⃣ Run the Web App
python app.py


5️⃣ Open in Browser
👉 Go to: http://127.0.0.1:5000/

Example Input:

Enter your health parameters in the form:

Pregnancies: 2

Glucose: 130

Blood Pressure: 80

Skin Thickness: 25

Insulin: 100

BMI: 28.5

Diabetes Pedigree Function: 0.45

Age: 35

👉 Example Output:
Prediction: Diabetes Detected (78% probability)


🔹 Prediction Result
Tech Stack

Frontend: HTML, CSS, JavaScript (Dashboard with animations & charts)
Backend: Flask (Python)

Machine Learning: RandomForestClassifier (Scikit-learn)

Data Handling: Pandas, NumPy

📌 Future Improvements
Add support for more diseases (Heart Disease, Cancer, etc.)

Deploy on Render / Heroku / Streamlit for public access

Improve model with hyperparameter tuning

👨‍💻 Author
👤 Your Name:Sarthak R Shetty

GitHub: @Sarthakrshetty

LinkedIn:www.linkedin.com/in/sarthak-r-shetty22



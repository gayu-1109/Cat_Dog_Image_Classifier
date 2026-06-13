🐶🐱 CNN Dog vs Cat Classifier

📌 Project Overview
This is a Deep Learning Image Classification Web App built using Convolutional Neural Networks (CNN) and deployed using Flask.
The model predicts whether an uploaded image is a Dog 🐶 or Cat 🐱 in real-time through a simple web interface.

🛠 Tech Stack
Python 🐍
TensorFlow / Keras 🤖
Flask 🌐
NumPy
HTML / CSS

⚙️ How to Run This Project

1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Train the model
python train_model.py

👉 This will generate:
dog_cat_model.h5

3️⃣ Run Flask app
python app.py

4️⃣ Open in browser
http://127.0.0.1:5000/

⚠️ Important Note
The trained model file (dog_cat_model.h5) is not included in this repository due to GitHub file size limitations.
👉 To generate it locally, run:
python train_model.py

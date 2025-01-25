# Car Price Prediction Web Application 🚗💰

This project is a **machine learning-powered web application** for predicting car prices based on various features like brand, year, mileage, engine specifications, and more. It uses **Streamlit** for the frontend and is implemented in Python.

---

## Features 🎯

- **Interactive UI** for inputting car details such as brand, year of manufacture, mileage, etc.
- Predicts car prices using a **pre-trained machine learning model**.
- Includes dropdowns, sliders, and buttons for a user-friendly experience.
- Supports car brands, fuel types, and other categorical variables seamlessly.

---

## Requirements 🛠️

Ensure you have the following installed:

- Python 3.7+
- Streamlit
- Pandas
- NumPy
- Pickle

---

## Installation and Setup 🚀

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```
   
2.Install the required dependencies:
 ```bash
pip install -r requirements.txt
```

3.Place the model.pkl file (pre-trained ML model) and Cardetails.csv (dataset) in the project directory.

4.Run the application:
```bash
streamlit run app.py
```

5.Open your browser and go to:
```bash
http://localhost:8501
```

## Usage 💻
Select or input the car's details using the interactive widgets.
Click the "Predict" button.
The predicted car price will be displayed on the screen.

## File Structure 📂
app.py: Main application script.
model.pkl: Pre-trained machine learning model (required).
Cardetails.csv: Dataset for car details (required).

## Example Input and Output 🔍
# Input
- **Car Brand**: Maruti
- **Year**: 2015
- **KMs Driven**: 45,000
- **Fuel Type**: Petrol
- **Seller Type**: Dealer
- **Transmission Type**: Manual
- **Owner**: First Owner
- **Mileage**: 20 kmpl
- **Engine**: 1200 cc
- **Max Power**: 85 bhp
- **Seats**: 5
# Output
- **Predicted Car Price**: ₹4,50,000

## Contributing 🤝
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License 📄
This project is licensed under the MIT License.

## Acknowledgments 🙌
- Streamlit for providing an excellent framework for building interactive web applications.
- The dataset and machine learning model used for this project.

## Happy Coding! 💻✨

You can modify sections like the GitHub repository link or license if needed. Let me know if you'd like help adding anything else!

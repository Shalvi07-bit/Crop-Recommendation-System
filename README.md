1.Crop Recommendation System 
This project recommends the best crop to cultivate based on soil and weather conditions using machine learning.

## Technologies Used

- Python
- Flask (for the web app)
- scikit-learn (for model training)
- pandas, numpy (for data manipulation)
- HTML (for the frontend)

##  Files

- `app.py` - Main Flask application.
- `ML PROJECT CROP_RECC.ipynb` - Notebook for data analysis and model training.
- `model.pkl` - Trained model saved using pickle.
- `standscaler.pkl`, `minmaxscaler.pkl` - Scalers used for data preprocessing.
- `Crop_recommendation.csv` - Dataset.
- `templates/index.html` - Frontend template.
- `requirements.txt` - Python dependencies.

2.Install dependencies:
pip install -r requirements.txt

3.Start the Flask app:
python app.py

4.Open in your browser:
http://127.0.0.1:5000/

5.Structure :
Crop_Recommendation_System/
│
├── app.py # Flask web application
├── model.pkl # Trained Random Forest model
├── minmaxscaler.pkl # MinMax Scaler used in preprocessing
├── standscaler.pkl # Standard Scaler used in preprocessing
├── ML PROJECT CROP_RECC.ipynb # Jupyter notebook for training & analysis
├── requirements.txt # List of required Python packages
├── README.md # Project overview 
├── templates/
│ └── index.html # HTML template for the web interface
├── static
├── Crop_recommendation.csv # Dataset used
└── pivot_*.csv # Pivot tables for EDA

---



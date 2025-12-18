Medical Diagnosis Using AI
A machine learning project for medical diagnosis using AI techniques to predict diseases from patient data. Built with Python and common ML libraries for healthcare applications.

Features
Analyzes patient symptoms and medical records for disease prediction

Implements classification models for accurate diagnosis

Includes data preprocessing, training, and evaluation pipelines

Supports multiple disease categories from the dataset

Project Structure
text
medical-diagonosis-using-ai/
├── Project2_files/
│   ├── Medical diagnosis using AI/
│   │   ├── datasets/          # Training and test data
│   │   ├── notebooks/         # Jupyter notebooks for analysis
│   │   ├── models/            # Trained model files
│   │   ├── src/               # Python source code
│   │   └── results/           # Evaluation metrics and visualizations
Tech Stack
Python 3.8+

Scikit-learn for ML algorithms

Pandas & NumPy for data handling

Matplotlib & Seaborn for visualizations

Jupyter Notebook for experimentation

Quick Start
Clone the repository

bash
git clone https://github.com/pradeepan1/medical-diagonosis-using-ai.git
cd medical-diagonosis-using-ai
Install dependencies

bash
pip install -r requirements.txt
Run the main notebook

bash
cd Project2_files/"Medical diagnosis using AI"
jupyter notebook main.ipynb
Usage
Load the dataset and run prediction:

python
from src.model import DiseasePredictor
predictor = DiseasePredictor()
prediction = predictor.predict(patient_data)
print(f"Predicted diagnosis: {prediction}")
Results
Accuracy: 92% on test set

Supported Diseases: Diabetes, Heart Disease, COVID-19, and more

Model comparison available in results/model_comparison.png

Contributing
Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add some AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open Pull Request

License
MIT License - see LICENSE file.

Contact
Pradeepan - @pradeepan1

⭐ Star this repo if you found it helpful!

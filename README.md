
# Iris Flower Classification Web App

This is a Machine Learning minor project that uses a Decision Tree Classifier to predict the type of Iris flower based on four input features: sepal length, sepal width, petal length, and petal width. The project includes a Flask-based web application that runs locally and allows users to interact with the ML model via a simple HTML form.

## Project Structure

ris_flower_classifier/ ├── app.py # Flask web server ├── train_model.py # Model training script ├── model.pkl # Trained ML model ├── templates/ │ └── index.html # Web UI template └── static/ └── style.css # CSS for styling the page


## Technologies Used

- Python 3.x
- Flask
- Scikit-learn
- Pandas
- HTML/CSS
- VS Code (IDE)

## How to Run

### Step 1: Install Dependencies

Make sure you have Python installed. Then install the required libraries:

```bash
pip install flask scikit-learn pandas

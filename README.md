# Food Delivery Time Prediction Web Application

This is a web application built using Flask that predicts the delivery time for a delivery based on various factors. The application uses a linear regression algorithm to process input data and provide an estimated delivery time.

## Getting Started

### Prerequisites

Before running the application, make sure you have the following installed:

- Python (>=3.8)
- Required packages listed in `requirements.txt`

### Installation

1. Clone the repository:

  git clone <https://github.com/MKGourab/Food-Delivery-Time-Prediction>

2.Install the required packages using pip:

    pip install -r requirements.txt

3.Usage:
    - Run the application:

    - Open a web browser and navigate to `http://localhost:5000/` to access the application.

    - Fill out the form with relevant details and submit to get a delivery time prediction.

## Project Structure

<pre>
<code>
.
├── .ebextensions/                    # Elastic Beanstalk configuration files
│   └── python.config                 # Configuration for Python environment
├── .elasticbeanstalk/                # Elastic Beanstalk specific files
│   └── config.yml                    # Elastic Beanstalk configuration file
├── Notebook/                         # Jupyter notebooks and data for analysis
│   ├── eda.ipynb                     # Exploratory Data Analysis notebook
│   ├── model_training.ipynb          # Model Training notebook
│   └── data.csv                      # Dataset used for analysis and training
├── templates/                        # Flask HTML templates (if applicable)
├── artifacts/                        # Model and data artifacts
│   ├── model.pkl                     # Serialized machine learning model
│   ├── preprocessor.pkl              # Serialized data preprocessor
│   ├── raw.csv                       # Original raw data
│   ├── train.csv                     # Processed training data
│   └── test.csv                      # Processed testing data
├── src/                              # Source code directory
│   ├── components/                   # Components of your application
│   │   ├── __init__.py               # Initialization for components
│   │   ├── data_ingestion.py         # Data ingestion module
│   │   ├── data_transformation.py    # Data transformation module
│   │   └── model_trainer.py          # Model training module
│   ├── pipeline/                     # Application pipelines
│   │   ├── __init__.py               # Initialization for pipelines
│   │   ├── prediction_pipeline.py    # Prediction pipeline module
│   │   └── training_pipeline.py      # Training pipeline module
│   ├── __init__.py                   # Initialization for src package
│   ├── exception.py                  # Custom exception
│   ├── logger.py                     # Logging setup
│   └── utils.py                      # Utility functions
├── application.py                    # Main entry point for Flask app
├── requirements.txt                  # List of required Python packages
└── README.md                         # Project documentation

</code>
</pre>


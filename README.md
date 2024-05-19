# Model Builder Web Application

## Project Description

The Model Builder Web Application is designed to assist data scientists in streamlining the process of building, evaluating, and deploying machine learning models. This web-based application provides functionalities for uploading datasets, performing data cleaning operations, selecting algorithms, configuring model parameters, and evaluating model performance. The application aims to simplify and automate the machine learning workflow, making it accessible and efficient for users.

## Key Functionalities

1. **User Authentication and Management:**
   - **Secure User Registration and Login:**
     - Users can create an account by providing a username, email, and password.
     - Passwords are securely hashed and stored in the database.
     - Users can log in with their credentials to access the application.
   - **User Profile Management:**
     - Users can view and update their profile information.
     - Profile settings include changing the password and updating contact information.

2. **Dataset Management:**
   - **Upload Datasets:**
     - Users can upload datasets in CSV format.
     - The upload process includes providing metadata such as the dataset name, description, and upload date.
   - **View and Manage Datasets:**
     - Users can view a list of their uploaded datasets.
     - Each dataset entry displays metadata and provides options to view, edit, or delete the dataset.
   - **Metadata Management:**
     - Users can update the metadata associated with each dataset, such as renaming the dataset or updating its description.

3. **Data Cleaning:**
   - **Handling Missing Values:**
     - Users can choose methods to handle missing values, such as filling with mean/median, forward/backward fill, or removing rows/columns with missing values.
   - **Normalization:**
     - Users can apply normalization techniques like min-max scaling or standardization to their datasets.
   - **Encoding Categorical Variables:**
     - Users can encode categorical variables using techniques like one-hot encoding or label encoding.
   - **Tracking Data Cleaning Operations:**
     - The application logs and tracks all data cleaning operations applied to datasets, allowing users to review and revert changes if necessary.

4. **Model Building:**
   - **Algorithm Selection:**
     - Users can choose from a variety of machine learning algorithms (e.g., Linear Regression, Decision Trees, K-Nearest Neighbors, etc.).
   - **Configuring Algorithm Parameters:**
     - Each algorithm comes with configurable parameters that users can adjust to optimize model performance.
   - **Training Models:**
     - Users can train models on their cleaned datasets, with real-time feedback on training progress.
   - **Saving Models:**
     - Trained models are saved and stored, allowing users to reuse and deploy them for predictions.

5. **Model Evaluation:**
   - **Evaluation Metrics:**
     - The application provides a range of evaluation metrics depending on the model type (e.g., accuracy, precision, recall for classification; RMSE, MAE for regression).
   - **Visualizing Performance:**
     - Users can visualize model performance through graphs and charts, such as confusion matrices, ROC curves, and scatter plots of predictions vs. actual values.
   - **Storing Evaluation Results:**
     - Evaluation results are stored and can be reviewed later, allowing users to compare different models and configurations.

6. **Prediction:**
   - **Making Predictions:**
     - Users can use their trained models to make predictions on new data.
     - The application allows batch predictions by uploading new datasets or single predictions through an input form.
   - **Storing and Viewing Predictions:**
     - Predictions are stored and linked to the corresponding models and input data.
     - Users can view the prediction results, download them as CSV files, or visualize them within the application.

## Technology Stack

- **Frontend:** HTML, CSS
- **Backend:** Python (Flask)
- **Database:** PostgreSQL (using SQLAlchemy ORM)
- **Machine Learning Libraries:** scikit-learn, pandas, numpy

## Installation and Setup

### Prerequisites

- Python 3.x
- PostgreSQL

### Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/hasibahmad1995/ML-model-builder.git

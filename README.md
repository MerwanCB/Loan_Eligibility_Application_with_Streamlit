# Loan Eligibility Application with Streamlit

## Overview

This project is a simple web application built with Streamlit. It uses a machine learning model to predict whether a person might be eligible for a loan based on the information they provide. This helps users get a quick idea of their loan eligibility status.

## Links

*   **GitHub Repository:** [https://github.com/MerwanCB/Loan_Eligibility_Application_with_Streamlit.git](https://github.com/MerwanCB/Loan_Eligibility_Application_with_Streamlit.git)
*   **Live Streamlit App:** [https://loaneligibilityapplicationwithapp-px4bcsr2c6tm5agya29rvk.streamlit.app/](https://loaneligibilityapplicationwithapp-px4bcsr2c6tm5agya29rvk.streamlit.app/)

## Features

*   Allows users to input their details relevant to loan applications (e.g., income, loan amount, credit history etc. - *adjust specifics based on your app's inputs*).
*   Provides an instant prediction on loan eligibility (Eligible / Not Eligible).
*   Simple and intuitive web interface powered by Streamlit.

## Technology Stack

*   Python
*   Streamlit (for the web application interface)
*   Pandas (for data manipulation)
*   Scikit-learn (for the machine learning model)

## Running the App Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MerwanCB/Loan_Eligibility_Application_with_Streamlit.git
    cd Loan_Eligibility_Application_with_Streamlit
    ```

2.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Streamlit application:**
    ```bash
    streamlit run streamlit_app.py
    ```

4.  Open your web browser and navigate to the local URL provided by Streamlit (usually `http://localhost:8501`).

## Project Structure


```
├── data/             # Raw and processed data
├── notebooks/        # Jupyter notebooks for exploration (if any)
├── src/              # Source code for data processing, features, model, etc.
│   ├── data/
│   ├── features/
│   ├── models/
│   └── visualization/
├── app.py            # Main Streamlit application script
├── main.py           # Orchestration script (if separate from Streamlit app)
├── requirements.txt  # Project dependencies
└── README.md         # This file
```
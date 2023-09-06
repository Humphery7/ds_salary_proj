# ds_salary_proj
## Resources : https://github.com/rohan-benjamin/Glassdoor-Scraper-Final/blob/main/glassdoor_scraper.ipynb,https://medium.com/@benjaminrohan010/scraping-glassdoor-using-selenium-and-python-2022-bd0065775aec <b/>

**TRAINED AN ML ALGORITHM AND CREATED A MODEL THAT PREDICTS THE SALARY OF A DATA SCIENTIST BASED ON THE JOB DESCRIPTION**


# Salary Predictor for Data Scientists

## Overview

This project implements a Machine Learning algorithm to predict the salary of a Data Scientist based on the job description. It includes a trained model and a Flask API for local deployment. Predicting salaries for data science positions is a valuable tool for both job seekers and employers to gain insights into salary expectations.

## Features

- **Machine Learning Model**: Utilizes a pre-trained machine learning model that has been trained on a dataset of job descriptions and corresponding salaries.

- **Flask API**: Provides a user-friendly interface for interacting with the model. Users can input job descriptions, and the API returns predicted salary estimates.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/salary-predictor.git
   ```

2. Navigate to the project directory:

   ```bash
   cd salary-predictor
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the Flask application:

   ```bash
   python app.py
   ```

7. Open your web browser and navigate to `http://localhost:5000` to access the salary prediction interface.

## Usage

1. Access the web interface at `http://localhost:5000`.

2. Enter a job description in the provided input field.

3. Click the "Predict Salary" button to obtain a salary estimate based on the input job description.

## Dataset

The machine learning model was trained on a dataset containing job descriptions and corresponding salaries. The dataset used for training is not included in this repository.

## License

This project has no LICENSE

## Acknowledgments

- Special thanks to (Glassdoor Datascience jobs)[https://www.glassdoor.com/Job/data-science-jobs-SRCH_KO0,12.htm] for providing the job description data used for training.
- Scrapping was done using Selenium API

## Contact

- **Author**: Your Name
- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/humpheryotu/)

---

Feel free to customize this README to provide more specific details about your project, such as the dataset source, model details, deployment instructions, and acknowledgments. Additionally, don't forget to replace placeholders like `yourusername`, `your.email@example.com`, and `Your LinkedIn Profile` with your actual information.

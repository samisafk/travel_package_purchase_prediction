# Travel Package Purchase Prediction

[![Streamlit App](https://img.shields.io/badge/Streamlit-App-orange)](https://travelpackagepurchasepredictor.streamlit.app/)

## Overview

The **Travel Package Purchase Prediction** project aims to predict the likelihood of a customer purchasing a travel package based on various demographic and behavioral factors. By analyzing customer data, this model assists travel companies in identifying potential buyers, thereby optimizing marketing strategies and enhancing sales efficiency.

## Problem Statement

Travel companies often face challenges in identifying which customers are likely to purchase their packages. Random marketing approaches can lead to increased costs without significant returns. This project addresses the need to predict customer purchase behavior, enabling targeted marketing and improved resource allocation.

## Data Description

The dataset used in this project includes the following features:

- **CustomerID**: Unique identifier for each customer
- **ProdTaken**: Indicates if the customer purchased a package (0: No, 1: Yes)
- **Age**: Customer's age
- **TypeofContact**: Method of contact (Company Invited or Self Inquiry)
- **CityTier**: Tier classification of the city based on development and facilities (1, 2, or 3)
- **Occupation**: Customer's occupation
- **Gender**: Customer's gender
- **NumberOfPersonVisiting**: Number of persons accompanying the customer
- **PreferredPropertyStar**: Preferred hotel property rating
- **MaritalStatus**: Customer's marital status
- **NumberOfTrips**: Average number of trips per year
- **Passport**: Possession of a passport (0: No, 1: Yes)
- **OwnCar**: Ownership of a car (0: No, 1: Yes)
- **NumberOfChildrenVisiting**: Number of children under 5 years accompanying the customer
- **Designation**: Customer's job designation
- **MonthlyIncome**: Customer's gross monthly income
- **PitchSatisfactionScore**: Satisfaction score of the sales pitch
- **ProductPitched**: Product presented by the salesperson
- **NumberOfFollowups**: Total number of follow-ups after the sales pitch
- **DurationOfPitch**: Duration of the sales pitch

*Note: The dataset is hypothetical and used solely for educational purposes.*

## Project Structure

The repository is organized as follows:

- **Introduction.py**: Contains the introduction and problem statement.
- **Prediction.py**: Includes the prediction model and related functions.
- **contact.py**: Manages contact information and related functionalities.
- **main.py**: The main script to run the Streamlit application.
- **requirements.txt**: Lists all the dependencies required to run the project.
- **logistic_model.sav**: Serialized logistic regression model used for predictions.
- **logo.png**: Logo image used in the application.

## Installation and Usage

To run the Streamlit application locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sahilgoyal7214/travel_package_purchase_prediction.git
   cd travel_package_purchase_prediction
   ```

2. **Install the required dependencies**:

   Ensure you have Python installed. Then, install the dependencies using:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application**:

   Launch the application with:

   ```bash
   streamlit run main.py
   ```

4. **Access the application**:

   Open your web browser and navigate to `http://localhost:8501` to interact with the app.

## Usage

The Streamlit application provides an interactive interface where users can input customer details to predict the likelihood of purchasing a travel package. By entering relevant information such as age, occupation, and contact method, users can obtain immediate predictions and insights.

## Contributing

Contributions to enhance the project are welcome. To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request detailing your changes.

## Authors

- [Riya Shukla](https://github.com/riya0785)
- [Sahil Goyal](https://www.github.com/sahilgoyal7214)
- [Sammer Khatwani](https://github.com/samisafk)

---

*For a live demo of the application, visit the [Streamlit App](https://travelpackagepurchasepredictor.streamlit.app/).* 

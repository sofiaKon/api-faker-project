# Fake Data Generation with Faker and Pandas

## Project Overview
This project demonstrates how to generate synthetic data for 1,000 individuals using the `Faker` library in Python. The generated data includes personal information such as name, age, address, phone number, and job title.  

An object-oriented approach is used by creating a `Person` class, and the generated data is then converted into a `pandas DataFrame` for easier analysis and processing.

## Objectives
- Generate fake data for 1,000 people
- Use a Python class to represent each person
- Store the generated data in a structured format
- Convert the data into a `pandas DataFrame`

## Technologies Used
- Python
- Faker
- Pandas
- Google Colab

## Project Structure
- `Person` class for creating fake person objects
- `Faker` library for generating synthetic personal data
- `pandas DataFrame` for storing and displaying the dataset


df = pd.DataFrame(people)

print(df.head())

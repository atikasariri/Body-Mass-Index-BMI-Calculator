# Body Mass Index (BMI) Calculator

A simple interactive Python application designed to calculate an individual's Body Mass Index (BMI) based on weight (in pounds) and height (in inches) following standard Centers for Disease Control and Prevention (CDC) guidelines.

_**Features**_

- **Interactive User Input**: Accepts user's name, weight (lbs), and height (inches).
- **BMI Calculation**: Uses the standard imperial BMI formula:
  $$\text{BMI} = \frac{\text{weight (lbs)} \times 703}{\text{height (inches)}^2}$$
- **Health Category Classification**: Classifies results into standard adult BMI categories:
  - **Underweight**: BMI < 18.5
  - **Healthy Weight**: 18.5 ≤ BMI ≤ 24.9
  - **Overweight**: 25.0 ≤ BMI < 29.9
  - **Obesity**: BMI ≥ 30.0
- **Validation**: Basic validation for non-zero/positive input values.


_**Project Structure**_

```text
bmi-calculator/
│
├── notebooks/             # Directory for Jupyter Notebooks
│   └── bmi_calculator.ipynb  # Interactive BMI calculator notebook
│
├── .gitignore             # Specifies files and directories ignored by Git
├── LICENSE                # Open-source license terms (MIT)
├── README.md              # Project documentation
└── requirements.txt       # Project dependencies

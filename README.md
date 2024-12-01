# Hospital Data Analysis with Logistic Regression

This project analyzes hospital patient data to explore the relationship between patient satisfaction scores and readmission rates using logistic regression. The program calculates key statistics, performs logistic regression, and visualizes the correlation between satisfaction and readmission.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Example Output](#example-output)

---

## Features
- Reads hospital data from a `.txt` file.
- Calculates:
  - Number of patients readmitted.
  - Average satisfaction scores for staff, cleanliness, food, comfort, and communication.
- Performs logistic regression to determine the relationship between overall satisfaction and readmission rates.
- Visualizes the correlation using a logistic regression curve.

---

## Requirements
This project requires the following to run:
- Python 3.7 or higher
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

---

## Usage
1. Place the `Week14Assignment.txt` file in the project directory.
2. Run the program:
   ```bash
   python main.py
   ```
3. Follow the prompts to view statistical outputs and the logistic regression plot.

---

## Example Output
### Sample Statistics:
```
Number of Patients Readmitted: 4
Average Staff Satisfaction: 4.00
Average Cleanliness Satisfaction: 3.40
Average Food Satisfaction: 4.20
Average Comfort Satisfaction: 3.80
Average Communication Satisfaction: 4.20
```

### Logistic Regression Results:
```
Coefficient: 0.7284
Intercept: -1.2234
Model Score (Accuracy): 0.8000
```

The output includes a logistic regression curve plotted against patient satisfaction scores.

---

## Files in the Repository
- `main.py`: The main script for analyzing data and performing logistic regression.
- `Week14Assignment.txt`: Example input data file containing patient records.
- `README.md`: This documentation file.

---
## Sample Output of the graph
<img width="1672" alt="Screenshot 2024-12-01 at 1 15 35 PM" src="https://github.com/user-attachments/assets/77e6b2be-bea9-4ef3-81b3-603fdbb8705e">

# Team Burbank EEP 153 Project 4
In this `README.md`, we will briefly introduce our project highlights and goals, as well as provide a general overview of our project and a brief guide to replicate our project code.

> *Be sure to check out the **[Replication](https://github.com/IvanChan511/EEP_153_Project_4#-replication)** Section before proceeding to replication.*

## 🌟 Highlights
Here are the quick highlights for our project:

- Our project specifically looks at two countries - **Senegal & Ethiopia**.
- We computed their **Food Demand System** respectively, and their **Nutrient System** subsequently.
- We compared the predicted nutrition to the recommended nutrition, and presented the **nutritional challenges** for both populations.
- We proposed **policies** relevant to both countries to address the nutritional challenge for both populations.
- **Unit tests** are written to ensure our code runs smoothly and error-free.


## ℹ️ Overview

This project analyzes differences in nutritional outcomes across Senegal and Ethiopia by comparing the nutrient composition of diets based on what a typical household consumes. Rather than categorizing foods into broad groups, we focus directly on total nutrient intake to better understand how diets translate into health-relevant outcomes.

After establishing cross-country differences, we identify specific nutrient deficiencies and surpluses within each population. We then assess whether complementarities exist, where one country’s surplus could potentially address another’s deficiency, highlighting opportunities for trade-based policy solutions.


### ✍️ Authors

- Food Demand System - Natalie
- Nutrient System - Sage & Inaaya
- Nutritional Challenges and Policy Goal - Amanda
- Policy Options - Aaron
- Unit Tests - Inaaya
- `README.md` - Ivan Chan

## 🚀 Replication

*To ensure a smooth replication in our Project Code, please read the following instructions.*

In the introduction of our compiled and subpart project code, we have a section on Importation and Installation. Please make sure the requirements text files are available in your local directory if you're running locally, and uncomment the code to install all necessary libraries. Then run the code block followed by the installation code to make sure you imported all the required libraries for our project code.

Below is an example of what you might see in our Project Code:

``` py
#%pip install -r requirements-estimation.txt
```
``` py
#%pip install -r requirements.txt -q
```
``` py
from eep153_tools.sheets import read_sheets
import pandas as pd
import numpy as np
...
```

## 💭 Feedback and Code Review

If you have suggestions and comments on the code, please start an [Issue](https://github.com/IvanChan511/EEP_153_Project_4/issues)!


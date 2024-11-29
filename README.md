
# Consumer Behavior and Shopping Habits Analysis (Final Project)

## Summary
This project analyzes consumer behavior and shopping habits using a detailed dataset. It leverages Python-based tools for data preparation, exploration, and predictive analytics. The findings are focused on key aspects of consumer behavior, including the impact of discounts, product preferences, customer loyalty, and demographic influence on purchasing patterns.

### Key Sections:
1. **Data Preparation and Cleaning**: Handles missing values, outliers, and transformations.
2. **Finding #1**: Impact of Discounts and Promotions on Sales.
3. **Finding #2**: Product Preferences and Seasonality Effects.
3. **Finding #3**: Customer Loyalty and Subscription Services:
   - Predictive models: Decision Trees and Random Forests.
4. **Finding #4**: Demographic Influence on Purchasing Patterns.

## Files
- **Notebook File**: Contains all code, markdown, and outputs for the analysis.

## Installation
1. Clone this repository:
   ```bash
   git clone <repository-link>
   cd <repository-name>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Team 2 - Consumer Behavior and Shopping Habits (Final Project).ipynb"
   ```
2. Run each cell sequentially to reproduce the analysis.

## Dependencies
- Python 3.7+
- Libraries:
  - `pandas`
  - `seaborn`
  - `numpy`
  - `matplotlib`
  - `sklearn`
  - `pydotplus`

## Sample Code
```python
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.tree import DecisionTreeClassifier
```

## Results
1. **Discounts and Promotions**: Significant impact on increasing sales.
2. **Product Preferences**: Seasonal trends influence demand.
3. **Customer Loyalty**: Subscription services drive repeat purchases.
4. **Demographics**: Age, income, and region play a major role in purchasing patterns.

## Contributing
Feel free to raise issues or submit pull requests to contribute to the project.

## License
This project is licensed under the MIT License.

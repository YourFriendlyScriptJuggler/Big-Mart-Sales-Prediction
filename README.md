Big Mart Sales Prediction
This repository contains a machine learning project for predicting sales of items at Big Mart outlets using historical sales data. The project involves exploratory data analysis (EDA), data preprocessing, visualization, and building a regression model using XGBoost.

Project Overview
The goal of this project is to predict the sales amount (Item_Outlet_Sales) for various products sold across different Big Mart outlets. The dataset includes item details, outlet information, and sales data.

Key tasks performed in this project:

Data loading and exploration

Handling missing data and data cleaning

Visualizing distribution and relationships of key features

Encoding categorical variables for modeling

Training an XGBoost regression model

Model evaluation and predictions

Dataset
The dataset Train.csv contains the following columns:

Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP

Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, Outlet_Type

Item_Outlet_Sales (target variable)

Dependencies
The project uses Python and the following libraries:

numpy

pandas

matplotlib

seaborn

scikit-learn

xgboost

Usage Instructions
Clone the repository:

bash
git clone <repository-url>
cd <repository-folder>
Install dependencies (suggested via pip):

bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Place the Train.csv dataset in the project folder.

Run the Jupyter notebook Big_Mart_Sales_Prediction.ipynb to perform data analysis and model training:

bash
jupyter notebook Big_Mart_Sales_Prediction.ipynb
Key Notes
Deprecated methods such as sns.distplot() have been updated to current alternatives sns.histplot() or sns.displot() for plotting.

Avoid using chained assignment with inplace=True on DataFrame slices to prevent future pandas warnings.

XGBoost's regression objective was updated from deprecated reg:linear to the current reg:squarederror.

Colorful and clear visualizations are used to show distributions and counts of key features with rainbow palettes applied via Seaborn.

Contact
For questions or suggestions, please open an issue or contact the repository maintainer.

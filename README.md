# Car-Data-Analysis
## 🚗 Car Dataset Analysis

This project explores a dataset of 428 cars with 15 features, including details about make, model, type, origin, engine, horsepower, fuel efficiency, weight, and price.

The goal of this project is to perform data analysis, visualization, and predictive modeling to uncover insights into the automotive market.

## 📂 Dataset

The dataset contains the following columns:

Make: Car brand (e.g., Toyota, BMW, Ford)

Model: Specific car model

Type: Category (Sedan, SUV, Sports, Wagon, Truck, etc.)

Origin: Region of origin (Asia, Europe, USA)

DriveTrain: FWD, RWD, AWD

MSRP: Manufacturer’s Suggested Retail Price (in $)

Invoice: Invoice price

EngineSize: Size of the engine (liters)

Cylinders: Number of engine cylinders

Horsepower: Engine horsepower

MPG_City: Fuel efficiency (city)

MPG_Highway: Fuel efficiency (highway)

Weight: Vehicle weight (lbs)

Wheelbase: Distance between front and rear axles (inches)

Length: Length of the car (inches)

Shape: (428, 15)

## 🔍 Analysis & Questions

Some of the key data analysis questions explored:

What is the distribution of categorical variables (Make, Type, Origin)?

Which Make (brand) has the most models?

What factors (Engine Size, Horsepower, Cylinders, Weight) explain car price (MSRP)?

Do heavier cars with bigger engines always have lower MPG?

Are there clusters of cars (luxury, economy, sports) using horsepower, weight, mpg, and price?

What is the profit margin (MSRP – Invoice) by brand?

Which car Type offers the best value (low price, high mileage)?

Can we predict car price (MSRP) using other features?

## 📊 Visualizations

The project includes various plots:

Barplot → Car count by Type / Make

Boxplot → MSRP distribution by Type

Scatter + Trend Line → Horsepower vs MSRP

Cluster Plots → KMeans on features (Horsepower, Weight, MPG, MSRP)

Heatmap → Correlation between numerical features

Example:

sns.boxplot(x="Type", y="MSRP", data=data)

## ⚙️ Machine Learning

Preprocessing

Handling missing values

Encoding categorical variables (LabelEncoder, OneHotEncoder)

Feature scaling (StandardScaler)

Models

Linear Regression → Predict MSRP

KMeans Clustering → Group cars into segments (Luxury, Economy, Sports)

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

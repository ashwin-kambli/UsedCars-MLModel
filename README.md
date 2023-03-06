# UsedCars-MLModel
This project is a machine learning model which predicts the price of used cars. 


## Dataset
The dataset used in this project is the Used Cars Dataset from Kaggle. This dataset contains over 500,000 used car listings scraped from Craigslist. The dataset includes features such as the make, model, year, mileage, price, and location of the car.

## Project Structure
<ul>
    <li><code>data/vehicles.csv</code>: contains the dataset used in the project. The original dataset from kaggle contained 3 million observations. This has been reduced to 426K to help speed up processing.</li>
    <li><code>images/</code>: contains the images and graphs used for reporting purposes in the notebook</li>
    <li><code>Used Car Sales - Price Prediction ML Model.ipynb</code>: this notebook covers all the CRISM-DM steps used in this project: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment</li>
    <li><code>README.md</code>: provides an overview of the project</li>
</ul>

## Requirements
The following packages are required to run this project:

<ul>
    <li>numpy</li>
    <li>pandas</li>
    <li>scipy</li>
    <li>scikit-learn</li>
    <li>seaborn</li>
    <li>matplotlib</li>
    <li>jupyter</li>
    <li>Python 3.9 or above</li>
</ul>

## Results
The best model used for this project was a linear regressor with a degree 2 polynomial complexity with a ridge cross validator. Using permutation importance, the following vehicle features were identified as important for predicting the target variable (price):
<ul>
    <li>Condition of the vehicle</li>
    <li>Drive - 4 WD</li>
    <li>Year, and</li>
    <li>Type - Pickup trucks seems to command a higher resale value</li>
</ul>

## Contributors
Ashwin Kambli (@ashwin-kambli)

## License
This project is licensed under the MIT License - see the <a href="LICENSE" target="_new">LICENSE</a> file for details.
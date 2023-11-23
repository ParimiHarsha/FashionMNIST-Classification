# ECEN758-FashionMNIST_Classification
In this project, we developed Machine Learning model XGBoost and Deep Learning model Convolutional Neural Network to classify articles of clothing using the FashionMNIST dataset. 

Please follow the below steps to set up the virtual environment, install all the required dependencies and run the python notebook

## Step 1: Set up virtual environment
1. install conda
2. Create new virtual environment using `conda create --name fmnist-env python=3.11`
3. Activate the conda environment using `conda activate fmnist-env`
4. Install all the required packages `pip install -r requirements.txt` 
    - Alternatively you can also run `pip-sync requirements.txt` which would delete unncessary packages
5. Install any other packages that you might require and add them to the requirements.in file

## Step 2: Running the FashionMNIST_classification.ipynb notebook
1. Open the jupyter notebook with the activated virtual environment
2. Run the cells one by one

## Project Website
Please find the project website here - https://parimiharsha.github.io/FashionMNIST-Classification/

### Additional Resources: Creating the requirements.txt file
You can create the `requirements.txt` file from `requirements.in` file using `pip-compile --output-file=requirements.txt requirements.in`
While using any new packages, first add them to the requirements.in file with the version number and then run `pip-sync`. This should install the new package and also ensure that all the other packages are correctly installed.

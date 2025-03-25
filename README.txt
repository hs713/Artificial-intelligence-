# How to Run the Jupyter Notebook

## Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- Jupyter Notebook or Jupyter Lab
- Required Python libraries:

  ```bash
  pip install numpy pandas matplotlib scikit-learn
  ```

  If you are working with the UCI HAR dataset, ensure you also have:
  
  ```bash
  pip install seaborn
  ```

## Running the Notebook

1. **Open the Jupyter Notebook**  
   Navigate to the directory containing the notebook and run:
   ```bash
   jupyter notebook
   ```
   Open `Principal_of_Artificial_Intelligence.ipynb` in your browser.

2. **Run the Notebook**  
   - Execute the cells one by one.
   - The first section trains a linear regression model on California housing data.
   - The second section trains an SVM model on the UCI HAR dataset (ensure the dataset is available in the specified directory).

3. **Understanding the Outputs**  
   - The regression model will plot the relationship between income and house prices.
   - The classification model will output evaluation metrics like accuracy and confusion matrix.

## Additional Notes
- The UCI HAR dataset must be downloaded and placed in the correct directory.
- Modify dataset paths in the notebook if necessary.

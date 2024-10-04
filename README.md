# Air Quality Analysis Project: Tiantian Station

## How to Run the Dashboard
Please follow these steps to run the Air Quality Analysis Dashboard:

### Setup Environment
1. **Create and Activate Python Environment**:
   - If using Conda (ensure [Conda](https://docs.conda.io/en/latest/) is installed):
     ```
     conda create --name airquality-ds python=3.9
     conda activate airquality-ds
     ```
   - If using venv (standard Python environment tool):
     ```
     python -m venv airquality-ds
     source airquality-ds/bin/activate  # On Windows use `airquality-ds\Scripts\activate`
     ```

2. **Install Required Packages**:
   - The following packages are necessary for running the analysis and the dashboard:
     ```
     pip install pandas numpy scipy matplotlib seaborn streamlit statsmodels
     ```

     or you can do
     ```
     pip install -r requirements.txt

### Run the Streamlit App
1. **Navigate to the Project Directory** where `dashboard.py` is located.

2. **Run the Streamlit App**:
    ```
    streamlit run dashboard.py
    ```

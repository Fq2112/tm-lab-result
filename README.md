# Project 2: Lab Results Requirements
![TrustMedis](https://github.com/Fq2112/tm-lab-result/blob/main/images/logo.webp "Logo TrustMedis")

#### This is an application that allow users to determine their lab results based on certain reference values contained in the csv file.
![CSV](https://github.com/Fq2112/tm-lab-result/blob/main/images/csv.png "CSV File")

### Built With
* [Python](https://www.python.org/)
* [JupyterLab](https://jupyter.org/)

## Getting Started
Follow this step guide to prepare the requirement system before using the apps
1. Download and install [Python](https://www.python.org/downloads/)
2. Clone this repo
    ```sh
   git clone https://github.com/Fq2112/tm-lab-result.git
   ```
3. Install [JupyterLab](https://jupyter.org/install) 
    ```sh
   pip install jupyterlab
   ```
4. Run JupyterLab
   ```sh
   jupyter-lab
   ```

## How to Use
Follow this step guide to use the apps 
1. Open the ``main.ipynb`` file
2. Run the apps by hit the ``ctrl + enter`` buttons or just click the ``play icon`` on the header
   ![APPS](https://github.com/Fq2112/tm-lab-result/blob/main/images/run.png "Run Apps")
3. Go down, type the Test ID value inside the textbox based on the CSV, and hit enter
   ![ID](https://github.com/Fq2112/tm-lab-result/blob/main/images/input-id.png "Test ID")
4. Then, type the Test Result value and hit enter and hit enter
   ![RESULT](https://github.com/Fq2112/tm-lab-result/blob/main/images/input-result.png "Test Result")

## Conclusion
The apps will automatically compare the input value with the CSV file
1. When the test result value is lying between the reference value, then it's NORMAL 
2. When the test result value is higher than the reference value, then it's HIGHER
3. When the test result value is lower than the reference value, then it's LOWER

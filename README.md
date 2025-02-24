How to Run This Project

1. Add Files:
   - Add all the project files into VSCode or any similar development platform.

2. Set Up Anaconda:
   - Ensure Anaconda is installed on your system. If not, download and install it from [here](https://www.anaconda.com/).
   - Open Anaconda Prompt and create a virtual environment:
     ```
     conda create --name myenv python=3.9
     ```
   - Activate the environment:
     ```
     conda activate myenv
     ```

3. Install Python Extension:
   - Ensure that the Python extension is installed in your development environment (VSCode, for example).

4. Install Dependencies:
   - Open the terminal (or Anaconda Prompt) and navigate to the project directory.
   - Run the following command to install the required dependencies:
     ```
     pip install -r requirements.txt
     ```

5. Extract Required Files:
   - The following files need to be extracted from Jupyter Notebook:
     - `artefacts/movie_list.pkl`
     - `artefacts/similarity.pkl`
   - Run the commands in:
     ```
     /jupyter notebook/Recommender system.ipynb
     ```

6. Run the Server:
   - Open the terminal and navigate to the project directory.
   - Run the following command to start the server:
     ```
     streamlit run app.py
     ```
Created by divxodyssey



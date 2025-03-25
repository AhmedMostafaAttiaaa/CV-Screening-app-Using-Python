# Resume Screening App  

This is a **Resume Screening App** built using **Python** and **Machine Learning**. It allows users to analyze resumes and extract relevant information efficiently.

## Installation & Setup  
Follow the steps below to set up and run the application.

### 1. Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/your-username/Resume-Screening-App.git
cd Resume-Screening-App

## Create & Activate a Virtual Environment
It is recommended to use a virtual environment to manage dependencies.

- For Windows:
python -m venv venv
venv\Scripts\activate

- For Mac/Linux:
python3 -m venv venv
source venv/bin/activate

3. Install Dependencies
Once the virtual environment is activated, install the required dependencies:
pip install -r requirements.txt

## Running the Application using Streamlit
streamlit run app.py


Convert to Executable (.exe)
- pip install pyinstaller
- pyinstaller --noconsole --onefile --add-data "venv/Lib/site-packages/streamlit;streamlit/" app.py


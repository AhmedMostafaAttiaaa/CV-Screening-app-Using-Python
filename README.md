# Resume Screening App  

This is a **Resume Screening App** built using **Python** and **Machine Learning**. It allows users to analyze resumes and extract relevant information efficiently.

## Installation & Setup  
Follow the steps below to set up and run the application.

```bash
# 1. Clone the Repository
git clone https://github.com/your-username/Resume-Screening-App.git
cd Resume-Screening-App

```bash
# 2. Create & Activate a Virtual Environment
# For Windows:
python -m venv venv
venv\Scripts\activate

# For Mac/Linux:
python3 -m venv venv
source venv/bin/activate

```bash
# 3. Install Dependencies
pip install -r requirements.txt

```bash
# 4. Running the Application using Streamlit
streamlit run app.py

# 5. Convert to Executable (.exe)
# Install PyInstaller
pip install pyinstaller

# Create the Executable
pyinstaller --noconsole --onefile --add-data "venv/Lib/site-packages/streamlit;streamlit/" app.py

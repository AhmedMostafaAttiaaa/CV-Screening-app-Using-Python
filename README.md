# Resume Screening App  

This is a **Resume Screening App** built using **Python** and **Machine Learning**. It allows users to analyze resumes and extract relevant information efficiently.

## Installation & Setup  
Follow the steps below to set up and run the application.

### 1. Clone the Repository  
First, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/Resume-Screening-App.git
cd Resume-Screening-App
```

### 2. Create & Activate a Virtual Environment  
It is recommended to use a virtual environment to manage dependencies.

#### For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### For Mac/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies  
Once the virtual environment is activated, install the required dependencies:

```bash
pip install -r requirements.txt
```

### 4. Running the Application using Streamlit  
To start the application, run the following command:

```bash
streamlit run app.py
```

### 5. Convert to Executable (.exe)  
If you want to convert the app into a standalone `.exe` file, follow these steps:

#### Install PyInstaller:
```bash
pip install pyinstaller
```

#### Create the Executable:
```bash
pyinstaller --noconsole --onefile --add-data "venv/Lib/site-packages/streamlit;streamlit/" app.py
```

After running the above command, the executable file will be located inside the `dist` folder.

## Notes  
- Ensure you have **Python 3.7+** installed before running the commands.
- If you encounter any issues, consider running the commands with administrator privileges.
- For further customization, modify the `app.py` file as needed.

---  
- By **Ahmed Mostafa**

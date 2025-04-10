# Password-Strength-Checker
# Password Generator and Strength Checker

This is a **Streamlit-based web application** that allows users to generate secure passwords and check their password strength.

## Features
- **Password Generator:**
  - Customize password length (8-25 characters)
  - Include/exclude uppercase letters, lowercase letters, numbers, and special characters
  - Generates a secure random password based on user preferences
- **Password Strength Checker:**
  - Analyzes the strength of a given password
  - Provides feedback on whether the password is Very Weak, Weak, Medium, Strong, or Very Strong

## Technologies Used
- Python
- Streamlit
- Random & String modules

## Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Syeda-Rubab/Password-Checker.git
   cd password-tool
   ```
2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. **Run the Streamlit application:**
   ```sh
   streamlit run app.py
   ```
2. Open your browser and go to `http://localhost:8501/`

## File Structure
```
password-tool/
│── app.py               # Main application script
│── requirements.txt     # Dependencies
│── README.md            # Project Documentation
```

## Dependencies
Make sure you have the following installed:
- Python 3.x
- Streamlit

To install dependencies, run:
```sh
pip install -r requirements.txt
```


## Author
Developed by **Syeda Rubab**. Feel free to contribute or report issues!

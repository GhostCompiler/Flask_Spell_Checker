# Flask Spell Checker

A simple web-based spell checker built using **Flask** and **PySpellChecker** to correct misspelled words.

## Features
- User-friendly web interface for spell checking
- Corrects individual words and sentences
- Uses `pyspellchecker` for accurate spell correction
- Simple and lightweight Flask application

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- PySpellChecker

## Installation

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/Flask_Spell_Checker.git
cd Flask_Spell_Checker
```

2. **Create a Virtual Environment** *(Recommended)*
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

## Usage

1. **Run the Flask App**
```bash
python app.py
```

2. **Open in Browser**
Go to: [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

3. **Enter a word or sentence** and get corrected spelling suggestions.

## File Structure
```
Flask_Spell_Checker/
│── static/
│   ├── styles.css  # CSS for styling
│   ├── script.js   # JavaScript (if needed)
│── templates/
│   ├── index.html  # Frontend UI
│── app.py          # Flask application
│── requirements.txt  # Required dependencies
│── README.md       # Project documentation
```

## Dependencies
The project uses the following Python packages:
```bash
Flask
pyspellchecker
```
---
### Enjoy coding! 🚀

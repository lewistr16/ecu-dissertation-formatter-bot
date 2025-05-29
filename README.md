# ECU Dissertation Formatter Bot

This Streamlit app helps doctoral students at East Carolina University format their Dissertation in Practice (DiP) in alignment with Graduate School and APA 7th edition guidelines. It automatically:

- Reviews for font, spacing, and alignment errors
- Adds page numbers (centered in the footer)
- Inserts a Table of Contents field
- Validates heading level usage
- Checks for required Appendix A (IRB approval)

## 🎓 Branding

Customized with East Carolina University's official colors and logo.

---

## 🖥️ Local Deployment Instructions

### 1. Clone or download the repository
```bash
git clone https://github.com/your-username/dissertation-formatter-ecu.git
cd dissertation-formatter-ecu
```

Or unzip the downloaded package and navigate into the folder.

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
streamlit run dissertation_formatter_app.py
```

Your browser will open automatically to the app.

---

## ☁️ Streamlit Cloud Deployment Instructions

1. Upload these files to a **public GitHub repository**.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud) and sign in.
3. Click **“New App”**.
4. Connect your GitHub repo and select:
   - `main` branch
   - `dissertation_formatter_app.py` as the main file
5. Click **“Deploy”**.

Your app will be live on a public Streamlit URL.

---

## 📄 Files

- `dissertation_formatter_app.py` — Main app logic
- `requirements.txt` — Python dependencies
- `README.md` — You're reading it!

---

## 📬 Contact

## 📬 Contact

Developed by Dr. Travis Lewis, Associate Professor of Educational Leadership  
East Carolina University | College of Education  
📧 Email: lewist16@ecu.edu  
🌐 [Educational Leadership at ECU](https://education.ecu.edu/leed/)

Go Pirates! 💜💛

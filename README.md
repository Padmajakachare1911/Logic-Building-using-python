# 🈯 English to Hindi Translator with Logic Restriction

## 💡 Description
This project is a logic-based English-to-Hindi word translator built using **Python**, **scikit-learn**, and **Tkinter GUI**. It includes a small custom dataset and uses a Decision Tree Classifier to translate simple English words into their Hindi equivalents.

### 🚫 Special Rule
- If a word starts with a **vowel (a, e, i, o, u)**:
  - It can **only be translated between 9 PM and 10 PM**.
  - Outside this time window, an error message will be shown.
- Words starting with **consonants** are translated without any time restriction.



## 📁 Project Structure

Hindi_Translator_Project/
│
├── english_hindi.csv # Custom dataset
├── model.pkl # Trained ML model (optional)
├── encoder.pkl # Label encoder (optional)
├── vectorizer.pkl # Text vectorizer (optional)
├── Hindi_Translator_Project.ipynb # Jupyter Notebook with all steps
├── README.md # Project README file


## 🛠️ Features
- English-to-Hindi translation using a trained ML model.
- GUI interface built with Tkinter.
- Input validation and custom logic for vowel-starting words.
- Displays translation output in real-time.
- Includes accuracy metrics and classification report.


## 🚀 How to Run
1. Clone or download this repository.
2. Open the Jupyter Notebook: `Hindi_Translator_Project.ipynb`
3. Run all the cells in order.
4. The GUI will launch allowing you to input English words and get Hindi translations.


## ✅ Requirements

- Python 3.x
- scikit-learn
- pandas
- tkinter
- joblib

Install required libraries using:

```bash
pip install pandas scikit-learn joblib

# AI-Powered-Learning-and-Career-Assistance-Platform
# Intelligent Career Guidance System 🎓💼

## Overview

The Intelligent Career Guidance System is a machine learning-powered web application designed to assist students—especially those in their pre-final and final years of engineering—in making informed career decisions. By analyzing a student's academic data and interests, the system provides tailored career role recommendations using advanced classification algorithms.

---

## Features 🚀

- 🔍 **Personalized Career Recommendations** based on academic and psychometric inputs.
- 🧠 **Machine Learning Prediction** using SVM for role classification and probability estimation.
- 🌐 **Web Interface** with quizzes and input forms to collect relevant data.
- 📊 **Dynamic Backend** storing and retrieving user responses and career outcomes.
- 💬 **Flask Integration** for model inference and rendering predictions to the user.
- 🛡️ **PHP & SQL Integration** for secure user data storage and login system (XAMPP setup).
- 📈 **Career Insights** covering 17+ IT job roles like AI/ML Specialist, Data Scientist, Cybersecurity Specialist, etc.

---

## Tech Stack 🧰

| Layer         | Tools/Frameworks                              |
|--------------|------------------------------------------------|
| **Frontend** | HTML, CSS, JavaScript                          |
| **Backend**  | Python (Flask), PHP                            |
| **Database** | MySQL (via XAMPP), SQL                         |
| **ML Model** | Scikit-learn, Pandas, NumPy                    |
| **Tools**    | XAMPP, VS Code, phpMyAdmin                     |

---

## How It Works 🛠️

1. **User Registration/Login** via PHP and MySQL.
2. **Student Inputs** academic performance and interest quiz data.
3. **Flask API** processes data through a trained SVM model (`careerlast.pkl`).
4. **Prediction Output** gives the top recommended job role and alternatives.
5. **Web Output** displays the suggestions using a clear and interactive UI.

---

## Installation & Setup 🧪

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/intelligent-career-guidance.git
    cd intelligent-career-guidance
    ```

2. Set up the virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
    pip install -r requirements.txt
    ```

3. Set up XAMPP and import the database:
    - Start Apache and MySQL using XAMPP.
    - Open phpMyAdmin, import `career_db.sql` (if provided).

4. Run the Flask server:
    ```bash
    python app.py
    ```

5. Open your browser and go to:
    ```
    http://localhost:5000/
    ```

---

## Project Highlights 🌟

- Reduced reliance on manual counselling by providing ML-driven suggestions.
- Combined psychometric and academic inputs for holistic evaluation.
- Offers recruiters an easy way to match students to job roles based on skill prediction.

---

## Future Enhancements 🔮

- Add **email integration** to send detailed career reports to students.
- Support **multiple languages** for regional accessibility.
- Include **resume evaluation and improvement suggestions**.

---

## Contributors

- **Sowjanya Yararjala** – Developer & Project Lead

---

## License

This project is open-source and free to use under the [MIT License](LICENSE).


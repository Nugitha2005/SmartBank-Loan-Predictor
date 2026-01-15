# SmartBank Loan Predictor 🏦

A desktop application designed to predict loan eligibility using Machine Learning and provide personalized, human-like explanations using Generative AI.

Overview
This application takes user financial details (income, loan amount, credit history, etc.) and uses a **Random Forest Classifier** to determine if a loan should be approved or rejected. It then connects to the **Groq API (Llama 3)** to generate a professional explanation for the decision, simulating a real bank manager.

**Milestone:** This project marks my first practical implementation of Machine Learning algorithms, bridging the gap between theoretical Data Science concepts and real-world software development.

Key Features
* **Machine Learning Model:** Predicts loan status based on historical data.
* **AI-Powered Insights:** Generates natural language explanations for every decision using the Groq API.
* **GUI:** User-friendly interface built with Python Tkinter and designed in Figma.

Tech Stack
* **Language:** Python 3.10+
* **GUI:** Tkinter, Tkinter Designer
* **Machine Learning:** Scikit-Learn, Pandas, Joblib
* **AI Integration:** Groq API (Llama-3.3-70b-versatile)

Acknowledgments & Credits
* **Development:** Built by [Your Name] as a Data Science & Software Engineering project.
* **Learning Journey:** This repository serves as my first hands-on project using ML algorithms, demonstrating my ability to build and deploy predictive models.
* **AI Assistance:** Special thanks to AI tools for providing guidance on integrating the **Groq API** and structuring the backend logic for the AI overview features.

How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install pandas scikit-learn groq`
3.  Add your Groq API Key in `gui.py`.
4.  Run the application: `python gui.py`

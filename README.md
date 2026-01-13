# 🎓 AI Fitness & Diet Planner

[![Streamlit App]
**🔴 Live Demo:** [Click here to try the app!](https://ai-fitness-planner-jes.streamlit.app/)

A personalized, budget-friendly workout and diet planner powered by Llama 3 (via Groq) and built with Streamlit. This application helps to generate custom fitness plans that respect their time, limited equipment, and grocery budget.

## 🚀 Features

* **Personalized Routine:** Generates specific workout schedules based on age, gender, stats, and goals (Weight Loss, Muscle Gain, etc.).
* **Budget-Smart Grocery Lists:** Creates a consolidated weekly shopping list tailored to budgets (Low, Moderate, Flexible) and local currency.
* **Dynamic Calorie Math:** Automatically calculates maintenance calories and adjusts them based on user targets (e.g., "Lose 0.5kg/week").
* **"Ask the Coach" Chat:** An interactive AI chat feature allows users to ask follow-up questions about their plan (e.g., "What can I substitute for tofu?" or "How do I do a plank?").
* **PDF Export:** One-click download of the full plan and grocery list as a formatted PDF.

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **AI Model:** Llama 3.3 70B (via Groq API)
* **PDF Generation:** FPDF
* **Language:** Python 3.9+

## 📦 Installation (Run Locally)

If you want to run this code on your own machine instead of the cloud:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/ai-fitness-planner.git](https://github.com/YOUR_USERNAME/ai-fitness-planner.git)
    cd ai-fitness-planner
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up Environment Variables:**
    * Create a file named `.env` in the root directory.
    * Add your Groq API key inside it:
        ```env
        GROQ_KEY=gsk_your_actual_api_key_here
        ```

4.  **Run the App:**
    ```bash
    streamlit run planner.py
    ```

## 📂 Project Structure

```text
ai-fitness-planner/
├── planner.py           # Main application code
├── requirements.txt     # Python dependencies
├── .env                 # API keys (Not uploaded to GitHub)
└── README.md            # Project documentation

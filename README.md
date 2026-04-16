# 🏏 T20 Cricket Score Predictor

A web-based machine learning application built with Streamlit that predicts the final score of a T20 cricket match based on live match conditions such as current score, overs, wickets, teams, and city.

---

## 🔍 Features

- Select Batting and Bowling teams  
- Choose the match city  
- Input live match details:
  - Current Score  
  - Overs Completed  
  - Wickets Out  
  - Runs in the Last 5 Overs  
- 📊 Get a predicted final score instantly  

---

## 🚀 Tech Stack

- Python  
- Streamlit – UI framework  
- XGBoost – ML model  
- Scikit-learn – Pipeline & preprocessing  
- Pandas, NumPy – Data handling  

---

## 🧠 Model

The model uses **XGBRegressor** to predict the final score of a T20 match based on:

- Batting team  
- Bowling team  
- Match city  
- Current score  
- Balls left  
- Wickets left  
- Current run rate  
- Runs in the last 5 overs  

The trained pipeline is saved as:

```
pipe.pkl
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cricket-score-predictor.git
cd cricket-score-predictor
```

### 2. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate it:

- **Windows**
```bash
venv\Scripts\activate
```

- **Linux / macOS**
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

## 📂 Project Structure

```
cricket-score-predictor/
│── app.py
│── pipe.pkl
│── requirements.txt
│── README.md
```

---

## ✨ Future Improvements

- 📡 Live match API integration  
- 📊 Graph-based score progression  
- 🧠 Deep learning model enhancements  
- 🌍 More leagues and match formats  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

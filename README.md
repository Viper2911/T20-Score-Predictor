🏏 T20 Cricket Score Predictor
A web-based machine learning app built with Streamlit that predicts the final score of a T20 cricket match based on live match conditions like current score, overs, wickets, teams, and city.

🔍 Features
Select Batting and Bowling teams
Choose the City where the match is played
Input:
Current Score
Overs Completed
Wickets Out
Runs in the Last 5 Overs
Get a Predicted Final Score
🚀 Tech Stack
Python
Streamlit – UI framework
XGBoost – ML model
Scikit-learn – Pipeline & preprocessing
Pandas, NumPy – Data handling
🧠 Model
The model is trained using XGBRegressor to predict the final score of a T20 match based on:

Batting team
Bowling team
Match city
Current score
Balls left
Wickets left
Current run rate
Runs in the last 5 overs
The trained pipeline is saved as pipe.pkl.

📦 Installation
git clone https://github.com/your-username/cricket-score-predictor.git
cd cricket-score-predictor

# (optional) create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# install dependencies
pip install -r requirements.txt

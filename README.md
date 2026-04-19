🏋️ AI Sports Performance & Injury Prevention System
An AI-powered application that analyzes exercise posture using computer vision and provides real-time feedback and injury risk detection.

🚀 Features
📸 Image-based posture analysis
🎥 Video-based posture analysis
🧍‍♂️ Human pose detection using MediaPipe
📐 Joint angle calculation (knee, hip, elbow)
🏋️ Supports multiple exercises:
Squat
Push-up
Lunge
Plank
⚠️ Detects posture issues & potential injury risks
🤖 AI Coach for personalized feedback
🖥️ Interactive UI using Streamlit
🧠 How It Works
User uploads an image or video
MediaPipe extracts body landmarks (33 points)
Joint angles are calculated using vector math
Rule-based logic evaluates posture
Feedback + AI Coach advice is generated
🛠️ Tech Stack
Python
MediaPipe
OpenCV
NumPy
Streamlit
📂 Project Structure
SportsApp/ │── app_streamlit.py # Main application (UI + backend) │── requirements.txt # Dependencies │── README.md # Project documentation

▶️ How to Run Locally
pip install -r requirements.txt
streamlit run app_streamlit.py

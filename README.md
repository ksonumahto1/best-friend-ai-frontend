# best-friend-ai

📌 Best Friend AI – Real-Time Communication Skill Coach
Tech Stack: React, TypeScript, Flask (Python), WebRTC, Recharts, HTML5, CSS3 Tools Used: Replit, Firebase (Auth + Firestore planned), MediaPipe (planned), FFmpeg, GitHub
🔍 Overview: Best Friend AI is an interactive web application that helps users improve their communication skills through realistic scenario-based video roleplays. The user selects a situation—like a job interview or presentation—and records a response using their webcam. The app then provides feedback on verbal and non-verbal communication.
💡 Key Features:
🎭 Scenario Engine: Choose scenes such as Job Interview, First Date, or Presentation Skills.
📹 Webcam Integration: Record videos in-browser using react-webcam.
📤 Video Upload + Flask Backend: Seamlessly uploads the recording to a Flask server for analysis.
📊 AI Feedback (Simulated in current version):
Eye Contact
Smile
Voice Clarity
Posture
Overall Confidence Score
📈 Progress Tracker: Visualize scores for each scenario using dynamic Recharts bar graphs.
🔁 Replay Mode: Users can retry scenes and track improvement over time.
🔧 How It Works (Simplified Version):
Frontend built in React + TypeScript
Video recorded using browser webcam
Sent via POST request to Flask API (/api/analyze-video)
Flask server currently returns simulated AI feedback
Plans to integrate real AI-based analysis using MediaPipe, OpenCV, and Librosa
🚀 Future Plans:
Real-time feedback using computer vision and audio signal processing
Firebase Firestore integration for storing user sessions
Multi-user support and gamified progression

“This project reflects my passion for combining AI, behavioral psychology, and real-time analytics to help people communicate better in professional and personal scenarios.”

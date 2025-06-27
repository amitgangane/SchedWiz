# SchedWiz - Your AI Study Wizard


Overview
SchedWiz is an AI-powered study scheduler designed to help students optimize their study plans, reduce decision fatigue, and improve academic performance. It creates personalized, adaptive study schedules by considering individual student information, preferences, and performance data. 


Problem Motivation:
Many students face challenges such as lack of structure, unclear study paths, rigid plans that don't adapt to individual needs, and a general lack of intelligent guidance. Traditional study schedules often fail to adjust to personal factors like energy levels or pace, leading to difficulties in structuring days, staying motivated, and prioritizing tasks. 


Proposed Solution:
SchedWiz offers an AI-driven system that generates tailored study plans. It aims to improve focus, engagement, and academic success by providing a structured yet flexible approach to learning. The system predicts student performance and risk levels using PySpark and machine learning. Students input their scores, exam dates, and difficulty levels via a user-friendly Streamlit interface, and the AI instantly generates a personalized schedule, prioritizing subjects based on urgency and lower scores.


Key Features:
  Personalized Study Plans: Tailored to individual student data, preferences, and performance. 
  Adaptive Scheduling: Adjusts based on input like exam dates, difficulty levels, and latest       scores. 
  Performance Prediction: Utilizes machine learning to predict student performance and risk. 
  User-Friendly Interface: Built with Streamlit for easy interaction. 
  Prioritization: Prioritizes subjects with higher urgency and lower scores.


Technologies Used: 
The project leverages the following technologies:
  Python 
  PyTorch 
  Spark / PySpark 
  Streamlit 
  Pandas 
  NumPy 
  Scikit-learn (for preprocessing, metrics like 
  accuracy_score, classification_report) 
  Matplotlib 
  Seaborn 
  datetime module for date handling


Dataset and Exploratory Data Analysis (EDA)
The project utilizes datasets including:
  studentInfo.csv 
  studentAssessment.csv 
  StudentVLE.csv 
  assessments.csv

EDA was performed to check for null values and derive summary statistics for the datasets. 

Methodology:
The methodology involves developing an AI-powered system using PySpark, machine learning, and Streamlit. It predicts student performance and risk levels and generates adaptive study schedules.


Challenges and Future Improvements
Challenges Encountered
  Imbalanced Data: Reduced prediction accuracy for high performers. 
  Real-time Schedule Reshuffling: Complex to implement. 
  Backend Logic and UI Integration: Merging these took significant effort. 
  Data Access: Difficulty accessing real-time information despite no missing values in student     performance data. 
  People Resistance: Instructors and advisors might resist adopting AI tools. 
  System Compatibility: Ensuring compatibility with existing academic infrastructure. 
  Culture Shift: Moving from intuition-based planning to analytics-guided decisions. 

Next Steps & Future Improvements
  Improve Model Accuracy: Using class balancing techniques. 
  Real-time Progress Tracking: Add this to dynamically adapt plans. 
  Expand Input Fields: Incorporate features like energy levels or topic difficulty. 
  Data Integration: Integrate with institutional LMS and standardize digital gradebooks. 
  User Adoption: Conduct training sessions and transparently communicate model benefits and        limitations. 
  Promote Analytics: Encourage analytics as a complement to human decision-making.

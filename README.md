# Agriculture Advisory System

## 1. Project Overview
The Agriculture Advisory System is a web-based application designed to help farmers make better agricultural decisions. It provides crop recommendations and agricultural suggestions based on soil conditions, weather information, and environmental factors.

## 2. Project Objectives
- Recommend suitable crops based on soil conditions.
- Provide agricultural guidance to farmers.
- Help farmers improve crop productivity.
- Support better irrigation and fertilizer management.
- Reduce farming risks through data-driven recommendations.

## 3. Technologies Used
- **Programming Language:** Python
- **Backend Framework:** FastAPI / Flask
- **Frontend:** React.js
- **Database:** PostgreSQL
- **Machine Learning:** Scikit-learn
- **API Testing:** Postman
- **Version Control:** Git and GitHub

## 4. Key Features
- Farmer registration and login.
- Soil and weather data collection.
- Crop recommendation.
- Fertilizer suggestions.
- Agricultural information management.
- REST API integration.
- Database management.

## 5. Project Architecture
1. Frontend collects farmer inputs.
2. Backend APIs receive the information.
3. PostgreSQL stores farmer and agricultural data.
4. Machine learning processes the input data.
5. The system returns suitable crop recommendations.

## 6. Installation and Setup

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd agriculture-advisory-system
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
uvicorn main:app --reload
```

## 7. API Testing
Use Postman to test REST APIs such as:
- Farmer Registration
- Farmer Login
- Crop Recommendation
- Soil Information
- Fertilizer Recommendation

## 8. Expected Outcome
The system provides useful agricultural recommendations based on available input data, helping farmers make informed decisions and improve productivity.

## 9. Conclusion
The Agriculture Advisory System uses Python, REST APIs, databases, and machine learning to provide technology-based agricultural assistance to farmers.

## Nutrition Health Application using Generative AI

### Introduction
This application is a personalized nutrition advisor that leverages Generative AI to analyze food items from images and provide detailed nutritional insights. The application can identify food items from images and provide information such as calorie counts, nutritional breakdowns, health assessments, and dietary recommendations. This project showcases how Generative AI can be used in health and nutrition management to provide users with useful insights about their meals.


### Technologies Used
  - Python – Used for backend logic and API integration.
  - Google Gemini Pro Vision API – Used for analyzing food images.
  - Streamlit – Used to build the interactive web application.


### Installation

#### Prerequisites
Before running the application, make sure the following requirements are available:
  - Python 3.10 or above
  - Google Gemini API Key

#### Clone the Repository

```bash
# Clone the Repository
git clone https://github.com/archna13/Nutrition-Health-Application-using-Generative-AI.git
```

#### Create a Virtual Environment

```bash
python -m venv .venv
```

#### Activate the Virtual Environment

```bash
.venv\Scripts\activate     # Windows
source .venv/bin/activate  # Linux / macOS
```

#### Install Dependencies

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

#### Configure Environment Variables

Create a `.env` file in the project root directory and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_google_api_key
```

#### Start the Application

```bash
streamlit run app.py
```


### Key Features

#### AI-Powered Food Analysis

The application uses the Google Gemini Pro Vision API to analyze food items from uploaded images.
It identifies the food items present in the image and provides relevant nutrition-related insights.

#### Calorie Analysis

The application analyzes the identified food items and provides an estimated total calorie count.
This helps users understand the approximate calorie content of the meal they are consuming.

#### Comprehensive Nutritional Breakdown

The application provides a detailed nutritional breakdown of the analyzed meal.
It includes information about carbohydrates, fats, proteins, fibers, and sugars.

#### Health Evaluation

The application evaluates the analyzed meal and provides an assessment of its overall healthiness.
This gives users a better understanding of how the meal may fit into their dietary goals.

#### Dietary Recommendations

The application provides dietary recommendations based on the analyzed food and the user's dietary goals.
These insights help users better understand their meal choices and make informed dietary decisions.

#### Project Demo

The project demo demonstrates how the application analyzes food images and provides nutrition-related insights.
Watch the demo to get a better understanding of the application's functionality and user experience.

**Demo Video:** https://1drv.ms/v/c/8b3da0f8c820ba79/ESl616TNTPlNis-4lcnZtvkBZEzwo_0S1vLm6OXFf6U3Iw



### Conclusion
This project demonstrates the use of Generative AI for analyzing food images and providing personalized nutrition-related insights. By combining the Google Gemini Pro Vision API, Python, and Streamlit, the application provides users with information about food items, calorie counts, nutritional values, health assessments, and dietary recommendations.


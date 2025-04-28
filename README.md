# NutriNavigator - AI-Powered Personalized Health Recommendation System

A comprehensive nutrition and fitness platform that leverages Groq's ultra-fast Llama3-70b model to deliver customized health plans. The system processes user biometrics, dietary preferences, and health conditions to generate scientifically-valid recommendations.

# Technical Stack:
- Backend: Python, Flask, LangChain
- Frontend: HTML5, CSS3, Tailwind CSS, JavaScript
- AI/ML: Groq API, Llama3-70b, Prompt Engineering
- Infrastructure: Render (or your hosting platform)

# Project Workflow:

1. User Input Phase:
   - Collects 9 health parameters (age, weight, allergies, etc.)
   - Form validation and data sanitization

2. AI Processing Pipeline:
   - LangChain manages the Groq API integration
   - Custom prompt engineering for nutritional recommendations
   - Parallel processing of diet/fitness queries

3. Response Parsing:
   - Regex-based extraction of recommendations
   - Data cleaning and formatting
   - Categorization (Restaurants/Breakfast/Dinner/Workouts)

4. Presentation Layer:
   - Responsive UI with Tailwind CSS
   - Interactive result cards with hover effects
   - Smooth animations and transitions

5. Additional Features:
   - Privacy-focused design (GDPR compliant)
   - Error handling and fallback recommendations
   - Progressive enhancement for accessibility

# Key Innovations:
- Dynamic prompt templating for personalized outputs
- Multi-category recommendation generation in single API call
- Lightweight yet powerful architecture

# Run 
    python app.py

# Screenshot
![Screenshot 2025-04-28 203455](https://github.com/user-attachments/assets/80ddb4e8-bc58-44fa-b9a1-cac6aa8c7f84)
![Screenshot 2025-04-28 203509](https://github.com/user-attachments/assets/ecdcbdc3-86a1-456b-8e74-291f01426816)
![Screenshot 2025-04-28 203525](https://github.com/user-attachments/assets/975dcadf-4c8c-4182-b88a-c3298b778291)
![Screenshot 2025-04-28 203540](https://github.com/user-attachments/assets/d1c01099-bef9-440f-aaf1-877ad579d1e6)
![Screenshot 2025-04-28 203554](https://github.com/user-attachments/assets/6c818189-19e2-48d7-9aee-4235d59df045)
![Screenshot 2025-04-28 203649](https://github.com/user-attachments/assets/17e856b4-696a-4c1b-8ee3-a11f1ebdbbde)
![Screenshot 2025-04-28 203723](https://github.com/user-attachments/assets/8aec03e5-c16a-434f-8321-239278b28664)


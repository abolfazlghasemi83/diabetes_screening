# 🩺 Dr. Robotic  
### Rule-Based Diabetes Screening Tool — Client-Side & Privacy-First

[![Live Demo](https://abolfazlghasemi83.github.io/diabetes_screening/)](https://abolfazlghasemi83.github.io/diabetes_screening_V1.1/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

### 🚀 Version 2.0 Updates: AI & UX Overhaul

This major update transforms the core functionality from a simple rule-based system to a more robust, Machine Learning-based risk prediction model, alongside significant user experience (UX) and localization enhancements.
✅ Rules derived from clinical analysis using **IBM SPSS Modeler (C5.0 Decision Tree)**  

Built with pure HTML, CSS, and vanilla JavaScript — works offline after load.

### ✨ User Experience & Accessibility (UX)

Dark/Light Theme Toggle: Added full-page support for Dark Mode, including a persistent theme setting stored in localStorage.

Full Multi-Language Support (FA/EN): Added an English translation for all static and dynamic text elements, along with a language toggle button. Language preference is persistent using localStorage.

RTL/LTR Layout Switch: The page direction (dir) is automatically switched between Right-to-Left (Persian) and Left-to-Right (English) for optimal readability.

Persistent Form Data: Input values are saved to localStorage per language, so users can switch languages or refresh the page without losing their entered data.

Dynamic Result Display: The risk probability is categorized into Low (< 20%), Medium (20-50%), and High ($\ge$ 50%) with clear visual cues (colors) and personalized advice.

### 🛠️ Technical Refinements

BMI Calculation: Integrated client-side Body Mass Index (BMI) calculation (Weight / (Height in meters)²) directly into the prediction logic, requiring separate inputs for Weight (kg) and Height (cm)

Enhanced Input Validation: Added checks for empty or non-numeric fields and ensured that height is not zero or negative before calculating BMI.

---

## ▶️ [Live Demo](https://abolfazlghasemi83.github.io/diabetes_screening/)

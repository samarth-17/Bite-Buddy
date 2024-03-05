# Bite Buddy: Your AI-powered Calorie Counting Companion

- Bite Buddy is your fun and easy way to track your calorie intake using the power of image recognition and the Gemini Vision API. Whether you're snapping a picture of your plate at a restaurant or capturing your home-cooked creations, Bite Buddy is here to help!

## Deployment
Bite Buddy is deployed on Streamlit and can be accessed [Here👈](https://bite-buddy.streamlit.app/)

## Features:

- Effortless Calorie Tracking: Upload an image of your meal, or browse through our extensive food database to search for specific dishes. Bite Buddy will analyze your selection using the Gemini Vision API or retrieve information from the database to provide an estimated calorie count.

- User-friendly Interface: Bite Buddy's intuitive design makes it easy to track your calories on the go.

- Fun and Engaging: Say goodbye to bland calorie trackers! Bite Buddy's friendly demeanor keeps you motivated and informed about your dietary choices.


## Prerequisites:

- Python 3.x installed.
- A Google Gemini Pro Vision API key ([https://ai.google.dev/](https://ai.google.dev/)).

## Technologies:

- Python
- Streamlit
- Pillow
- Google GenerativeAI


## Setup:

1. **Clone the repository:**

   ```bash
   git clone https://<your_github_username>/calorie-counter.git
   ```
2. **Install dependencies:**
   ```cd calorie-counter
    pip install -r requirements.txt
    ```
3. **Create a .env file:**
  
   **Create a file named .env in the project directory.**

   **Add the following line to the file, replacing <YOUR_API_KEY> with your actual API key:**

   ``` 
   GOOGLE_API_KEY=<YOUR_API_KEY> 
   ```
   


4. **Run the application:**
    
    ```
    python app.py
    ```

**Usage:**

Open your web browser and navigate to `http://localhost:5000/`. Upload a food image and it will display the estimated calorie count.

**Note:**

* This project provides an estimate and may not be completely accurate. 
* It is recommended to consult with a registered dietitian or nutritionist for personalized dietary advice.
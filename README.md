Project Description

This project is a hand-gesture-based system to solve math problems using AI. It integrates computer vision, gesture recognition, and generative AI to create an interactive application. Using a webcam feed, the application detects hand gestures, tracks movements to draw on a canvas, and sends the drawn math problem to an AI model for solution. The results are displayed in real-time on a webpage powered by Streamlit.



The project demonstrates the integration of various technologies to achieve a creative and practical application of AI and computer vision. Key purposes include:

1>>Hand Gesture Recognition: Detect specific hand gestures using cvzone and Mediapipe.

2>>Drawing Interface: Utilize a fingertip to draw on a virtual canvas.

3>>AI-Powered Math Solver: Send the canvas content to an AI model (gemini-1.5-flash) for problem-solving and retrieve the solution.

4>>Usage of Streamlit to create an interactive web-based interface for displaying the real-time webcam feed, drawing canvas, and AI-generated solutions.

How to Run Locally
Prerequisites:

>>Python installed on your system.

>>A working webcam.

>>Internet connection (required for AI model interaction).

>>Install Required Libraries: Run the following commands to install dependencies:

bash command:

     pip install cvzone opencv-python-headless mediapipe numpy pillow streamlit google-generativeai

API Key:

>>Get an API key from Google Generative AI.

>>Create ur own API key.

>>Run the Application:

Save the script in a Python file, for e.g.,main.py.

>>Run the Streamlit app with:
run code in terminal

       streamlit run main.py
Using the Application:

The webpage will open in your default browser.

Ensure the webcam is active and allow permissions if prompted.
Use the following gestures:

>>Single Index Finger (Up): Draw on the canvas.

>>All Fingers (Up): Clear the canvas.

>>Three Fingers (Up):(index,middle,ring)-fingers.Will show the Output.

Output:

>>The left section displays the webcam feed and the drawing canvas.

>>The right section displays the AI's solution.

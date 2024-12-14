Steps to Install and Run the Project:
1.	Download or Copy the Code
Make sure you have the Python file (Mail File.py) saved on your computer. You can put it anywhere, but remember the location (like your Desktop).
2.	Install Python
o	Install Python from python.org if you don’t already have it.
o	Make sure to check the box "Add Python to PATH" during installation.
3.	Install Streamlit
o	Open your terminal or command prompt and type this:
pip install streamlit
4.	Install OpenAI Library
o	You’ll also need the OpenAI library for the project. Install it by running:
pip install openai
5.	Run the Streamlit App
o	Navigate to the folder where the Python file is saved. For example, if your file is saved at C:\Users\anish\OneDrive\Desktop\Olympai, do this:
cd "C:\Users\anish\OneDrive\Desktop\Olympai"
o	Now run the app with Streamlit by typing:
streamlit run "Mail File.py"
6.	See the App in Your Browser
o	Streamlit will automatically open the app in your default web browser. If it doesn’t, copy and paste the link from the terminal (usually something like http://localhost:8501) into your browser.
7.	Make Sure You Have an API Key
o	This project uses OpenAI. You’ll need an OpenAI API key to use the app.
o	Go to platform.openai.com and get your API key if you don’t have one already.
o	Replace the placeholder in the code (openai.api_key = "YOUR_API_KEY") with your actual API key.
8.	Done!
o	That’s it! The app should now be running. If you run into any issues, double-check the steps or feel free to ask for help.
________________________________________
Dependencies (Libraries Required)
•	Python 3.8+
•	Streamlit: For running the web interface.
•	OpenAI: For connecting with the AI API.


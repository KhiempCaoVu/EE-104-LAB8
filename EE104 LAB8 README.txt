WEB CRAWLER ***************************************
Python (version 7 to version 10). You can download Python version 10 from the official website: https://www.python.org/downloads/.
An OpenAI API key. You can obtain an API key by visiting the OpenAI API Keys page: https://platform.openai.com/account/api-keys.

Clone the full code for this tutorial from the OpenAI Cookbook GitHub repository and save it in a local directory on your computer. For example, you can put the files in C:\web-crawl-q-and-a. The repository can be found at: https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a.

Create a new folder named web-crawl-q-and-a using the Linux command md (make directory) in the PowerShell window.
Navigate to the newly created directory using the cd (change directory) command in PowerShell.

In the .env file, add the line OPENAI_API_KEY = "YOUR_OPENAI_API_KEY", replacing YOUR_OPENAI_API_KEY with the API key obtained in step 2.


Environment
In the PowerShell window, navigate to the web-crawl-q-and-a directory using the cd command.
Install the virtualenv package by running the command python install virtualenv (or c:\python310\Python install virtualenv if you need to use the absolute path).

Running AI 

In the PowerShell window, navigate to the web-crawl-q-and-a directory using the cd command.

Run the command pip install -r requirements.txt to install the required Python packages.

Run the command python web-qa.py to start the AI.
Open a web browser and navigate to http://localhost:5000 to access the AI's web interface.


FILE Q&A *************************************************

Install Python: If you don't already have Python installed on your computer, you'll need to download and install it from the official website. Make sure you install the latest version of Python.

Clone the repository: Clone the repository containing the code to your local machine using Git. If you don't have Git installed, you can download it from the official website.

Set up the API key: You need to obtain an OpenAI API key and set it up as an environment variable on your system. You can follow the instructions on the OpenAI website to get an API key and set it up on your system.


Start the app: Run the command "python app.py" in the terminal to start the Flask app.Open the app: Open a web browser and navigate to "http://localhost:5000" to use the app. You can enter a question in the input field and click the "Ask" button to get an answer.

Shutdown the app: To shutdown the app, press "Ctrl+C" in the terminal window.


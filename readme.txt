To run:
1)Install pytohn 3.8 or later.
	Linux: sudo apt-get install python3.8
	Windows: download from https://www.python.org/downloads/windows/. Make 	sure to select the option to add Python to your system's PATH 	environment variable during the installation process

2) Create a python environment.python -m venv myenv.

3) Activate the environment.
	Linux:myenv\Scripts\activate.bat
	Windows: source myenv/bin/activate

4) Install modules from requirement files. 
pip install -r .\src\requirements.txt

5) run run.bat or python .\src\main.py

Note:
Need to set the following environment variables:

TELEGRAM_BOT_TOKEN: A token for the telegram bot father.
MEDIASTACK_ACCESS_KEY: A token to access the Medastack API.
OPENAI_API_KEY: A token to acces OpenAI API.
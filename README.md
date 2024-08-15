# Chrome-Automation

Description:

This Python program is a simple way to opens up a number of websites using Google Chrome. It depends on the module webbrowser which has few fancy browser automation features but can be useful for doing simple stuff like opening up URLs.

Requirements:

Python 3(https://www.python.org/downloads/)

Installation:

No additional libraries are required for this script as it uses standard webbrowser module

Instructions:

Save the script as Python file such as chrome_opener.py.

Open terminal or command prompt and go to the folder where you save the code.

Run the function using this command:  

Bash

python chrome_opener.py

Use with caution.

Code Explanation:

Python

import webbrowser as wb

def webauto():

"""Opens a list of websites in Google Chrome."""



for url in URLS:

    print("Opening: " + url)   

    wb.open(url)# Simpler approach using webbrowser.open
Copy
Run the function
webauto()

Use with caution.

Explanation:

The line import webbrowser as wb brings in the entire internet browsing module into our program.”

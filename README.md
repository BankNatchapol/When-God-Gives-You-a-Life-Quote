# **When God Gives You a Life Quote**
### Azure Quantum Summer 2022 Hackathon

# Overview

Everyday is a great day, but it can be better if you get a great quote at the start of the day. Instead of getting it from some random people, get it directly from the god.
<br><br>
This project is about using Quantum Randomness to randomly give you a life quote (so i assume that the one who gives you the quote is god).

# Installation
```
pip install -r requirements.txt 
```

# Configuration
You need to insert *resource_id* and *location* of your Azure Quantum Workspace in ```config.py```.
```
resource_id = "ID"
location = "LOCATION"
```

# Usage
Using this command to run the code.
```
python main.py
```
After run the code, wait for Job run successfully (it'll take a few minutes). <br><br>
result:<br>
<img src="files/god_quote.png" height='410'>
# References
Thank you for the resources used in this project. <br>
Quote list : https://github.com/jcalazan/random-quotes/blob/master/db/randomquotes.csv, https://github.com/akhiltak/inspirational-quotes/blob/master/Quotes.csv <br>
Quote to image : https://github.com/NotCookey/Quote2Image
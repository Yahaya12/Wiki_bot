# Wiki_bot

This is a very simple python bot that reads you article summeries from wikipedia using an API wrapper, i made this out of boredom but feel free to fork it (tbh i'd really appreciate it if you do), i'm gonna reference the resources i used because they're super awesome and very well documented

# Current features
Reads out summeries of wikipedia articles as provided by the user

It can also read the entire article for you if the --f flag is provided

# Usage
Clone the repo
Install the dependencies via pip install Wikipedia-API pyttsx3
To run the script python wikibot.py t [--f] where t is the title of the article and --f is an optional arg in case you want to listen to the entire article
Example
summery : python wikibot.py "elon musk"

full article : python wikibot.py "tesla inc" --f
# The modules i used for this project 
WikipediaAPI, a very simple yet powerful wrapper for the wikipedia api and it has amazing features and an amazing documentation

pyttsx, an amazing and super simple text to speech module that can say whatever you want it to and also save the audio to a file


# Top Billboard Song Data Scraping Project
Hello everyone! I am a data science major in my first year of college. I made a project to share with all of you today. It will scrap the top song listed on the [Billboard Hot-100](https://www.billboard.com/charts/hot-100/) and the user can take 5 tries to guess what the top song is! It uses BeautifulSoup and Python to scrape the data and print everything to the terminal. <br><br>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fnos.jkt-1.neo.id%2Fcdc-s3%2Fimage%2F2025%2F04%2F19%2Fbillboardhot100-2025_3_68031f1ed9513.png&f=1&nofb=1&ipt=6f9df7d55380f76d213f8662db642bac285f2b509d76aab123d9127014a1daf2" width="400" alt="billboard hot 100"/> 

<br>

You can find the repo [here](https://github.com/CaptainSapphire/Top-Song-Guessing-Game/tree/main). <br><br>

## How it was made
I took inspiration from the [geeksforgeeks](https://www.geeksforgeeks.org/) project, [Quote Guessing Game](https://www.geeksforgeeks.org/python/quote-guessing-game-using-web-scraping-in-python/). I used Visual Studio Code as my IDE (Pycharm is another option, but any IDE that works on your respective system is fine), Python as my coding language, and [Beautiful Soup](https://pypi.org/project/beautifulsoup4/) as my python library for web scraping. <br>

I first took the Billboard Hot-100 URL and saved the top song and artist as two variables. I then made a simple for loop so the user can take 5 guesses to guess the song. Looking back now, I could've used a ```(while guess != answer and i !=5)``` and printed the amount of guesses, but given it's so few guesses, I figured it's fine to just keep it simple. Maybe I'll go back and print the number of guesses and just make a local iteration variable, and/or add how many guesses you have left. <br>

Anyway, the program clears the console/terminal at the end with ```os.system('cls')``` (if you have MacOS/Linux, use ```os.system('clear')```) and thanks the user for playing. 

## Issues I ran into
There were two main issues I encountered. <br>

Firstly, I was having trouble getting the answer from the page itself. I am used to web scraping using classes and selenium, so I had to familiarize myself with beautiful soup and find the element using the id instead (the class had some crazy long name, and didn't even work??). Secondly, I wanted to iterate through each item with a while loop, which would've looked something like this:
```
play = input("do you want to play for the next place? (y/n) ")
while (play.lower == "y"):
  ## same stuff as before, but now using an iteration "i," and treating the search ike finding an item in an array or list. 
```
However, that is unfortunately not how elements and html works, since each one has a unique id and I wouldn't be able to iterate through them. I could make a bunch of code blocks for each individual guess, but that feels unecessary based on what I was trying to achieve with this project.

## What did we learn?
I learned how to use Beautiful Soup to web scrape in Python, and some syntax errors along the way (as well as considering adding some user friendly features along the way. 

## Conclusion
Thank you so much for reading, and just a reminder to check out the project and run it yourself [here](https://github.com/CaptainSapphire/Top-Song-Guessing-Game/tree/main). <br><br>

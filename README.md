1.  What is the most influential book or blog post you’ve read regarding web development?
- The most influential blog post I've read during my time learning web development was Understanding Python Decorators in 12 Easy Steps by Simon Franklin. Decorators was on of the most hard things I needed to understand for the project Multi User blogs. Blogs had to use the Same template for every post a person made and anything interaction the post did so it needed to repeate code over and over and the pest way was with Decorators. The best `was*args` and `**kwargs` which helped a lot to have any decorator act as a stand in when building function during the project. 
2.  tell me about a web application you have built. Why did you choose to build it? What did you learn? What challenges did you face and how did you overcome them?
- A web application I had to built that I'm proud of it the Neighborhood-Map which was just a single page layout but was built on so much skilled learned thought my learning experiance with web development. I most I learn was simplifed code with the Use of Knockout and API thanks to google Maps and Foursquare. I lot of the challanges I'd faced was connecting the HTML to JavaScript with the modelViewViewModel method. Data-bind linking Function to the layout of the HTML. 
3.  Write a function in Python that takes a list of strings and returns a single string that is an HTML unordered list (<ul>...</ul>) of those strings. You should include a brief explanation of your code. Then, what would you have to consider if the original list was provided by user input?
```
def print_ul(strings):
  print("<ul>")
  for s in strings:
    ul = "<li>" + str(s) + "</li>"
    print(ul)
  print("</ul>")
  camping = ['tent', 'sleepingBag', 'water', 'boots', 'Clothes', 'flashlight', 'toiletpaper', 'snacks']
  print_ul(camping)
```
-Set up so the list will print in HTML format then define string, identify Array as string and then print string called camping. If the list is supplied by user input the function check for input being a list and contaning text to become a string for an array. 

4. List 2-3 attacks that web applications are vulnerable to. How do these attacks work? How can we prevent those attacks?
- One is SQL Injection which is the biggest problem a web application is vulnerable to due to being common and useful for both developers and attackers. The attacker can use a SQL command and force local databases to open up from a webpafe search box or if the web application has users in logins. 
- Another is Cross Site Request Forgery (CSRF) wich happens when a user is tricked into clicking a link or downloading a image that execute unwanted actions by a third party. 
- Best way to to prevent attacks like this is inclued Picture clicking or questions needed answering to ensure the request is being sent by a human user and not a bot. 
5. Here is some starter code for a Flask Web Application. Expand on that and include a route that simulates rolling two dice and returns the result in JSON. You should include a brief explanation of your code.

    ```
    from flask import Flask
    app = Flask(__name__)

    import json
    import random

    @app.route('/')
    def hello_world():
      return 'Hello World!'
    @app.route('/roll_dice/<int:n>/json')
	  def dice(n):
    rolls = []
    for i in range(n):
    	two_dice = random.randint(1, 6) + random.randint(1, 6)
      rolls.append(two_dice)
    return rolls
    if __name__ == '__main__':
      app.debug = True
      app.run()
    print(dice("add a number here");
    ```
-Added in a sepreate file from hello world I add the functionality of rolling two dice and returning a result as Print to the number or rolles added in print(dice(). 
6. If you were to start your full-stack developer position today, what would be your goals a year from now?
-For my goals in a year from now if I start my position today is to learn more knockout.js, python and css in more detail that I worked on couple of the projects to the work method of this company. Continue learning new technique in an enviorment that promotes continuous learning and career growth. 

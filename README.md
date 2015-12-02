

# Fortune Teller Challenge

At the end of these exercises today and tomorrow, you will have an App Engine application that performs [cold reading](https://en.wikipedia.org/wiki/Cold_reading) simulations. Set up a basic application, then read the requirements below and implement each path as specified. Note that the requirements may be vague, ambiguous, or just incomplete. Think about how you are deciding between different ways of implementing things.

##Paths

###**Fortune Cookie**

Path: /fortunecookie

Requirements:

1. When a user goes to this path, they shall see an image of a fortune cookie and receive a random fortune. [What library will you need to import?]

2. There shall be at least ten different fortunes.




###**Magic 8-Ball**

Path: /8ball

Requirements:

1. Users will eventually be prompted to enter a question when they go to this path. But for now, use a hardcoded question in the handler. userQuestion = "Will I have a good day today?"

2. Ten of the possible responses that the Magic 8‐ball can give shall be positive. Five of the possible responses that the Magic 8‐ball can give shall be negative. Five of the possible responses that the Magic 8‐ball can give shall be neutral. If you want, you can use the standard [responses](http://en.wikipedia.org/wiki/Magic_8_ball#Possible_answers).



## Done Early? Two Options
1. Tomorrow you will be able to include html and css files. For today you can write them in the same directory as your fortune teller application. You should have a an eightball.html file, a cookie.html file and you can send it a default string for now.

2. Alternatively, you can start to add the whirlybird feature in the Stretch lab below.

###**STRETCH: Whirlybird**

Path: /whirlybird

Based on the color and number that a user picks, a fortune is generated. Tomorrow, the user will be selecting a color and number using buttons. But for now hard code them. 
* userColor = blue
* userNumber = 3

Requirements:

You should read the color and number requirement so that you can understand the final project. For today (Monday) just worry about writing the logic that gives the fortune.

#### Colors

* When the user visits /whirlybird, they shall be prompted to pick a color: red, green, blue, and yellow. Each color shall be represented by a square button of that color. The buttons shall be arranged in 2x2 grid.

* The user shall select a color by clicking its associated button.

#### Numbers

* Once the user selects a color, they shall be prompted to pick a number.

* The user shall be allowed to pick any number between one and eight, inclusively, by clicking a button labeled with the number.

#### Fortunes

*  Once the user has selected both a color and a number, they shall be presented with a fortune

*  Each fortune shall be at least two sentences long.

* The sum of number the user selected and the number of letters in the color the user selected shall uniquely identify the fortune they receive. Which is to say, if that sum is equal for two different selections, the fortunes produced shall be the same.

<a href='https://learn.co/lessons/cssi-6-fortune-teller-first-steps' data-visibility='hidden'>View this lesson on Learn.co</a>

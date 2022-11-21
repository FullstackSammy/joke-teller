# Joke Teller | Javascript Project
[Live site](https://fullstacksammy.github.io/joke-teller/)

This is a fun project using a robot gif and two different APIs to make the robot tell you a joke.

![Image of responsiveness](/assests/images/response.jpg)

## User Stories

Create a joke telling text-to-speech API
- Use a text-to-speech API
- Get jokes from a Joke API
- Generate one joke at a time when pressing button
- When pressing button, text-to-speech API tells the joke


## Features

### Existing Features
- Infinite jokes told by a text-to-speech API
- Beautiful image (GIF) with matching background
- Click-friendly button to generate jokes

## Testing
I checked my code on the on the following sites:
- My CSS code on [Jigsaw](https://jigsaw.w3.org/css-validator/#validate_by_input) and it passed
- My HTML code on [W3](https://validator.w3.org/) and it passed
- My JavaScript code on [BeautifyTools](https://beautifytools.com/javascript-validator.php) and it passed

When you first land on the webpage, you are met by a robot gif, which is very cute to look at. 

![gif of robot](/robot.gif)

There is also a button with the text "Tell Me a Joke".

![image of landingpage](/assests/images/button.jpg)

When you press the button, a random joke from the joke API is generated and passed to the text-to-speech function, and a robotic voice tells the joke.
Here is an example, where I console.logged the generated joke two times by clicking the button.

![image of original source](/assests/images/joke1.jpg)

![image of original source](/assests/images/joke2.jpg)

## Bugs
No bugs were detected, so there was no need for any debugging

## Credits
- Credits to the Voicerss text-to-speech API. [Read the Documentation here](https://www.voicerss.org//api/)!
- To JokeAPI for the limitless funny jokes, adjusted to my liking. [Link to there site](https://sv443.net/jokeapi/v2/)
# thigns in my code

var start time/total seconds
var totaltime = 75;

var elapsedTime = 0;
Needs to restart with each game



* Potential HTML element
var form
var buttons for each answer
var startButton = document.getElementId('start-button')


var elapsed time
var start button
    With event listeners



Questins-List []

each item of the array will be an object built with these properties

    * Questions
    * List of possible answers
    * Correct Answers

# What kind of actions does my code need to perfom?

intervalfunction

When the user clicks the start button ,we need to start the first question.
    Event listeners

When a user clicks the answer button we need to validate the answer
    -if function
    if not correct we need to remove additional clock off the clock 

Need to be presented with another questions

We need to use an interval to create a countdown - setInterval() set to 1000 milliseconds
    - This will countdown for us every seccond
   - increment elapsedTime Calc 
   - calc current time left by subtracting total time - elapsed time
   - check to see if elapsed time is larger than total time (running out of time)
   - if it has reached 0 we need to end the game
   - this is a new variable for time left
   - Then we need to display to user textcontent property

Save the information in the browser (Local Storage)



** Clearing out HTML and then generating them all as a list to create thew new set of questions
    - There are some previous examples that you can find

# How are the different actions are going to run

* Clicking the start button with event listener
* Click an answer button to run validateAnswer();
- Need to create a function called validateAnswer();

# functions
function validateAnswer(){

    if (notValue)

    removeAdditionalTime();

}


* We can use bootstrap to create this
- But it is good to try and write the CSS by ourselves 
- We create our own questions



# SOURCES

- Click events, event delegation class
- Questions array you can step through with a function
- For how to set up questions look at beginning of Thursday nights class



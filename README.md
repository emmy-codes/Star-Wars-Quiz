# Star Wars Quiz - Personal Project 2

I wanted to continue the Star Trek theme into this second project, but after starting planning I decided I should make some new research on colour palettes and typography to ensure my grade is reached, so I will be going with a Star Wars quiz instead. This quiz will take the user through 10 questions from various Star Wars films, with a right and a wrong answer. There will be a visual cue upon choosing correctly or incorrectly to help the user to see how they answered.

On my future implementations on my Star Trek Museum project I noted that I wished to add a twinkling star background to the page but that would require JS. I think coding the background is going to showcase my JS abilities just as equally as the code used to write the quiz, so I feel like I will be covering my bases well on showing my understanding of basic JS.

((image of AIR of completed project to go here))

Link to the live site - [Star Wars Quiz](https://emmy-codes.github.io/Star-Wars-Quiz/)

---

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
* [Overcoming obstacles](#overcoming-obstacles)
  * [Getting Unstuck](#getting-unstuck)
  * [Bug Fixes](#bug-fixes)

* [Credits](#credits)
  * [Content](#content)
  * [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

### User Stories

The site will be a clean and concise, one page application, with a clear interface to allow for quick understanding of the page content and purpose. Since the site is going to be quite ambiguous, the new visitors and returning visitors goals will be the same.

The user should be able to:

* Read up on how the quiz works, either by clicking an information icon/button or with a short blurb of text.
* Track their score in real time after each question is answered.
* Have a visual indication on which was the right or wrong answer once they have made their choice.
* Have their score enlarged/highlighted at the end of the round.
* Have an option to reset the quiz and start again.
* Add-on after MVP to have localhost saving the scores locally on their machine.

## Design

### Colour Scheme

The main colours of the Star Wars opening theme is simply, black, white and yellow (for which I have found the nice hexcode of #FFE81F), along with the starry background I will be creating with HTML/CSS/JS. In case of needing further colours, I sourced a nice The Old Republic color palette created by someone on [Color-hex](https://www.color-hex.com/color-palette/22099)

![Color-hex Star Wars TOR colour palette](https://github.com/emmy-codes/Star-Trek-Quiz/assets/70635859/70b94671-d844-4b82-ba0c-a61ea9ac6f96)

((Image of final starry background to go here))

### Typography

I started looking up what sort of fonts could try to imitate the famous Star Wars logo and font. It isn't easy to replicate exactly with just Google Fonts but I chose the Roboto font with a sans-serif backup to come as close as possible whilst maintaining good UX/readability. I chose font weight 700 and 900 to keep the thick look of the original text.

![Star Wars Intro comparison image](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/59c83676-c835-4ce4-9254-2e22fac79661)
![Roboto Google Fonts 700weight](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/8d1c642e-2e6c-4b4d-bcfd-361b26fe8f41)
![Roboto Google Fonts 900weight](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/7bd3cd80-2010-4078-bd68-ef6f5c69d013)

### Imagery

At the time of planning I am uncertain if there will be any imagery used, as the background "image" will be coded by myself and the main theme of the text on Star Wars is the well-known yellow border, black background and white text. For the MVP I will not plan images but they may go in as an add-on once I've completed the bulk of my project.

### Wireframes

![Star Wars Quiz main screen](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/e2fa8911-1f16-4757-af6c-b76290109ed1)
![Star Wars Quiz how to play](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/5f88b9ed-18a7-4753-9adb-a456c5f2f29e)
![Star Wars Quiz questions](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/2770684f-ce1d-46cc-8054-08737d5453f7)

## Features

The key concept was to have a main window where you can see the score, and then a window would appear ontop of this one when the info/start game buttons were clicked. From there you could close the window with the X, and when playing the game you would click on one of the options to continue through the quiz, whilst being able to see your updated score in the main window behind the quiz window.

No header needed on this page, but there will be a footer with fake socials on it, along with a note about the quiz. A little Grogu currently resides in the favicon slot, although it's hard to see what it is for now, he may get swapped out.

((images of the final product on desktop, tablet and mobile))

### Future Implementations

In the future I would like to implement difficulty levels, as well as more options to choose from rather than the current 50/50 chance of choosing correctly or not.

### Accessibility

Due to the simple nature of the page there are few accessibility concerns. I chose a font that has a Star Wars essence without the grouping together of letters that happens on the official font, as that could impact screen reader's ability to separate the letters effectively.

In regards to the colour palette, the contrast of black, white and yellow allows for a clear, clean interface. 

I don't want to deviate from the original colour palette so I have to think of a good way to visually indicate whether the user has answered correctly or not, to avoid red/green colours on the answers as this can negatively impact the experience for colour blind users.

## Technologies Used

👩🏻‍💻 View an example of a completed Technologies Used section [here](https://github.com/kera-cudmore/Bully-Book-Club#Technologies-Used)


### Languages Used

HTML, CSS, JavaScript.

### Frameworks, Libraries & Programs Used

#### Programs

[Balsamiq](https://balsamiq.com/) - For creating my wireframes.

[Google Fonts](https://fonts.google.com/) - For the font family chosen.

[Am I Responsive](https://ui.dev/amiresponsive) - To retrieve good screenshots of responsiveness across devices.

[Github](https://github.com/) - For online storage of code, and deployment.

[VS Code](https://code.visualstudio.com/) - For writing my code.

[Coolors](https://coolors.co/) - Used to collect hexcode colour palette.

[Picresize](https://picresize.com/) - Used to resize images.

## Deployment & Local Development



### Deployment

![Deployment Star Wars Quiz](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/227fc071-6215-4219-bede-8abe4a349974)

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

Place instructions on how to fork your project here.

#### How to Clone

Place instructions on how to clone your project here.

## Testing


## Overcoming obstacles

Writing JavaScript can be done in so many ways, meaning you can produce the same result with 5 lines of code as you can for 20. Wanting to impart the DRY methodology as much as possible into my code I worked very hard to write as little code as possible. With the knowledge I had up until this point it was a challenge as what I had learned vs what I wanted to do didn't quite line up, so it took me a long time to get the first function written. Here are some of the obstacles I faced and how I managed to eventually succeed.

### Getting unstuck

My showQuizQuestions was going to be a big function to tackle. I wanted it to work for every iteration of the questions and answers instead of having lengthy for loops or extra functionality. At first I couldn't get it to work, as I was trying to target quiz.quizIndex which targets the properties of the array, rather than the index of the question. 

I took a look back at my learnings and tried picturing how I would target one question on the array, rather than all of them which felt like too big of a scope on my first try. That would involve using index[0]. That helped me to see that I needed to replace the numeric value with a variable that would be able to iterate through the questions later on. Thus came the variable quizIndex which could then be targeted inside the variable currentQuestionObject, named to help me picture that the variable is targetting the object property of question.

more notes here before the end fixes...

Finally I created the event listener that would trigger the showQuizQuestions function which is set to listen for "click" events attached to any interactive element with the "start-game" class. ((add about how that went wrong once game started) 

### Bug fixes 

When I wanted to start getting the score to update, my first thought was to simply create a variable containing the score data (using placeholders to start with) and add it to where the rest of my elements were being created.

Wrong.

My first attempt I put it inside the for loop, which then added the score element to each button. 

![scoreTally append not working](https://github.com/emmy-codes/Star-Wars-Quiz/assets/70635859/d9f954e5-6ee2-4ec7-ba09-15c47f1bace1)

I then tried doing the same thing but outside the for loop and added it to the section where I was appending the other elements, which worked, but for when I will work on updating the score I believe I'll need to be tracking the data outside of the functgion in the same way I am tracking the question index updates, so I declared the variable outside of the function.

## Credits

### Code

The modal dialog code was taken from MDNs guide with some tweaking and Googlign to get it to do what I want: [Dialog element guide](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)

### Content

[Parade](https://parade.com/1161189/alexandra-hurtado/star-wars-trivia/) - Where I sourced my quiz questions and answers from.

[ChatGPT](https://openai.com/) - For providing me with 3 incorrect answers to each question I used from Parade.
  
###  Acknowledgments

Less of an acknowledgement, more of an ode-to: my partner, for pair programming with me without offering any code solutions, but painstakingly taking me through the process of thinking logically, helping me to focus on where I had updated my source of truth during my code updates, for helping me to compartmentalise a problem and execute it step by step rather than looking at the big picture and panicking. For being there through it all, thankyou ❤️

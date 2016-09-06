# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
<http://i.imgur.com/Zt4Lwev.png>

-   The data structure you plan to use.
For users and games, I plan to use a javascript object for my data structure.
However, for the cells of a game, I am going to use an array for the "x" and "o"
data.

-   How you will take the markup of the game board and represent it in JS
The game board will essentially consist of empty divs. However, based off of a
users actions, certain events will be triggered, and JS will display the results
of the actions through jQuery.

-   How you plan to approach this project.
I plan to start by creating a wireframe and devising the game logic based off of
information in the API. After figuring out the game logic, I will begin setting
up the basic html layout and minimum necessary CSS to better visual the design
from my wireframe. Afterwards, I will incorporate the forms and connections with
the API in order to create players and games. Then, I will add in the game logic
from the beginning and see how everything connects together. Lastly, after
everything is functioning well, I will spend more time on the CSS styling and
creativity aspect of the game.

-   4-8 user stories for your game project.
As a user, I want a 'history' button so that I can view my past game
  results.
As a user, I want a 'game over' and 'results' window so that I know
  when and who has won each game.
As a user, I want the 'sign up' and 'log in' windows to be hidden when
  not needed because they are distracting and visually unattractive.
As a user, I want a way to tell whose turn it is so that a player does or
  cannot play twice.

-   How you plan to keep your code modular.
I am going to create multliple files that will be loaded by the browser through
script tags.

-   What creative spin will you add to your project.
In addition to using personalized CSS styles, I also want to get creative with
jquery and try to make sure that the page is very dynamic but fluid at the same
time.

-   How you will use version control to backup / track your project.
I will use a git repository hosted on Github and make frequent, cohesive commits
throughout the entire project. I will also try my best to make good and
descriptive commit messages.

-   Do you plan to attempt any of the bonuses.
No, I do not plan to attempt any of the bonuses at the moment.

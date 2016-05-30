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
      In my notebook, both web and mobile versions. Both versions have headers
      with player vs player, and the board underneath. web version will have
      room on the right for stats, maybe shown throughout the game, or hidden
      behind a button click.

-   The data structure you plan to use.
      Game board will be stored as an array to check game state, the user stats
      will be JSON strings.

-   How you will take the markup of the game board and represent it in JS
      I think I'm going to use buttons in divs that players can click to place
      their Xs and Os on the board, with PLACE PIECE HERE text replaced with
      the players piece when clicked, and made unclickable once it's been
      clicked once. Borders on specific sides will make the 9 squared tic tac
      toe shape.

-   How you plan to approach this project.
      I'm going to start with the JS template and build up from there. First I
      will work on getting the basic html structure of the page up, with options
      for sign up/sign ins for each player. Then start hooking the .on(click)
      functions into the buttons I've made. Once that is working, I'll start
      adding in code to keep track of what player clicked where, and when a
      win/tie occurs. This will probably be the longest and most difficult part
      of the project. Once all of that is coded, I will add in funcitonality to
      save and send send the relevant game stats to the user's account. Finally,
      I will work on my CSS code to set the correct spacing, colors, fonts, and
      style.  

-   4-8 user stories for your game project.
      "As a new user I want to sign up to play a game and save my future games"
      "As a player I want to sign in to play a game and see my past games"
      "As a player I want to play a game piece to make a move on the board"
      "As a player I want to see all the game pieces in play to decide my move"
      "As a player I want to know who wins the game, if there's a winner"
      "As a player I want to click a button to access to all of my games stats"

-   How you plan to keep your code modular.
      I'll separate my ui code from my event code from my AJAX success/failure
      code.

-   What creative spin will you add to your project.
      I'm not sure yet. I have a color theme in mind but I want to get it
      working before I think too much about any other extras. A few of the
      bonus challenges look interesting too, and will keep them in the back of
      my mind when structuring my app.

-   How you will use version control to backup / track your project.
      I will be committing to github early and often, and will use different
      branches for working on different aspects of the project - I will probably
      make a branch for any of the bonuses I attempt to complete.

-   Do you plan to attempt any of the bonuses.
      I would like to try if I have time!

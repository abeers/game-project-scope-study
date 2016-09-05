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
    My wireframes are on paper, and I don't have a scanner. I'm happy to share
    in person.

-   The data structure you plan to use.
    The game board will be divided into 9 cells, and the state of each cell will
    be represented by an array of strings.

-   How you will take the markup of the game board and represent it in JS
    The group of cells can be selected in jQuery by class, and they can be
    updated through jQuery methods, specifically addClass() to at least change
    the background color of the cells. Once I get the logic working, I plan to
    replace the background colors with images.

-   How you plan to approach this project.
    All logic will be client side. After a user signs in, the app will store
    this user and token. The user can then get games. Once they select one
    specific game (and get it from the api), the board will render based on the
    string values in the cell array of that game. The player turn will be
    determined, and a player will be able to click on a cell of the board. If
    the cell is filled, nothing will happen or a message will tell the user that
    that cell is occupied. If the cell is empty, the cell array will be updated
    with that value and a function will determine if that player has won. Once
    that is determined, an api update request will be made, the board will be
    rendered again, and the next turn can be taken.

-   4-8 user stories for your game project.
    As a player, I want to be able to see my unfinished games so I can finish
    them.

    As a player, I want to be able to customize my tokens so I can have a unique
    profile.

    As an administrator, I don't want any players to have access to other
    players' accounts.

    As a player, I want to be able to play against my friends on other devices
    so we don't have to share one computer.

    As a player, I want a single player mode so I don't always have to play
    against friends.

    As a player, I want to see how many games I've won and lost so I can compare
    with my friends.

    As a player, I want a new game experience because I've already mastered
    tic-tac-toe.

-   How you plan to keep your code modular.
    I plan to divide my code into as many small, reusable functions as possible,
    while keeping code organized into several files that correspond to their
    functionality.

-   What creative spin will you add to your project.
    In addition to completing the requirements of the project using a
    responsive, professional-looking layout and implementing multi-device
    support, I'd love to add a new spin on the actual game of tic-tac-toe. I
    think I can achieve this by allowing the other player to attempt to block
    the player whose turn it is. I don't want to focus on it too much before I
    complete my other goals, but I believe it can be achieved relatively easily.

-   How you will use version control to backup / track your project.
    I will add branches for each feature and commit frequently.

-   Do you plan to attempt any of the bonuses.
    Yes, I would love to implement multi-device support, possibly a chat system,
    and customizable tokens, in addition to my personal bonuses.

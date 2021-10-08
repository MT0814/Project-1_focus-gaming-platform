# Project 1: Focus Gaming Site - Developed by Team 6

## Description 

A gaming platform for easily filter, sorting free games and add them into your favorite list to play them whenever you desire.

### User Story

```
As a user, I want to see tiles of games so that I can choose what I want to play.

As a user, I want to sort games’ tiles by alphabetical titles and release date.

As a user, I want to filter games’ tiles by its platform so that I can find my specific game.

As a user, I want to select a game to play so that I can know if I like it or not.

As a user, I want to select a Pokémon game tile so that I can play the game.

As a user, I want to play the Pokémon game on the site so that I can have fun. 

As a user, I want to add 10 favorite games to the game collector box so that I can check them quickly.

As a user, I want to navigate to more pages to see more games tiles.
```

### Acceptance Criteria 

```
As a user, I want to see tiles of games so that I can choose what I want to play.
GIVEN tiles of games
WHEN I go to the site
THEN I can see all the games tiles

As a user, I want to filter games’ tiles by its platform so that I can find my specific game.
GIVEN Browser and PC platform as filter options
WHEN I select one of the filter options
THEN it shows me a result page with the game which meets my selection

As a user, I want to select a game to play so that I can know if I like it or not.
GIVEN all tiles can be clicked 
WHEN I click a tile of game
THEN it shows me the selected game page
THEN I can click the play button to play the game

As a user, I want to select a Pokémon game tile so that I can play the game.
As a user, I want to play the Pokémon game on the site so that I can have fun. 
GIVEN me a Pokémon game tile 
WHEN I click it
THEN it directs me to Pokémon game site

As a user, I want to add 10 favorite game to the game collector box so that I can check them quickly.
GIVEN an add icon on each game tile
WHEN I click the add icon
THEN it shall add that game to the game collector box
THEN it shall let me add up to 10 lists
```

## Html Page Layout:

    Navigation, Header,

    Main Section, Collapsible Pokemon card, Game Tiles,

    Left Section, Filter By, Sort By,

    Pagination

    Footer

## Implemented Features:

    1. Games tiles with Images, Url, Titles, Brief Game Description, Favorite Button, Redirect to new game in new tab.

    2. Adding game tile to favorites list.

    3. Filtering games by Platform - PC or Browser.

    4. Sorting Games by Titles and Release Date.

    5. Modal form to show favorite games list.

    6. Redirect to selected game from modal.

    7. Created Pokemon game using pokemon API.

    8. Redirect to Pokemon game to new tab.

    9. Pagination for 10 pages.

    10. Pokemon Game.

## Technologies used:

    HTML, CSS , JavaScript, jQuery

    Materialize CSS framework

    APIs:

    Free-To-Play Games API

    Pokémon API

## Tools used:

    VS Code, Git Bash, GitHub, GIT

    JIRA, Google Doc, Zoom, Slack

## License
[![License: MIT License](https://img.shields.io/badge/License-MIT%20License-yellow.svg)](https://www.gnu.org/licenses/MIT%20License)

## Others

1. Focus Gaming Platform screenshot

   ![index.html screenshot](./assets/images/screenshot.png)

2. [Published website](https://mt0814.github.io/Project-1_focus-gaming-platform/)

3. Please see the latest source code under "dev" branch.
   Note: "main" branch does not reflect the latest code.
   [Source code](https://github.com/KS1/UGameOn/tree/dev)

4. [Wireframes](https://github.com/KS1/UGameOn/blob/dev/Focus%20Project%20Wireframes.pdf)

5. [Demo Presentation](https://github.com/KS1/UGameOn/blob/dev/Focus%20Project%20Team6%20Demo%20Presentation.pdf)

6. [jira User Stories](https://project1-ugameon.atlassian.net/jira/software/projects/UG/boards/1/backlog)

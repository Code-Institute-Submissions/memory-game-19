<h1 align="center">
  <a href="#" target="_blank"><img src="img/memory-game.png" alt=" Halloween Memory Game"/></a>
</h1>

<div align="center"> 
Halloween memory game is an entertaining memory game for children. 
Features include fun animations, a mover counter, timer and an overall rating of your performance when finished. 
<br>

[View the Halloween memory game]()

</div>

## Table of Contents
1. [**UX**](#ux)
    - [**Project Goals**](#project-goals)
    - [**Player goals**](#player-goals)
    - [**Developer and Business Goals**](#developer-and-Business-Goals)
    - [**User Stories**](#user-stories)
    - [**Design choices**](#design-choices)
    - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies used**](#technologies-used)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

## UX

### Project Goals

The primary goal of PicFlip! is to provide a clean, intuitive and child friendly game to entertain and delight it's users.
PicFlip! has two target audiences: Pre-school children and their parents. 

#### Player goals

The central target audience for this game is pre-school children aged 1 to 5 years old.

Players goals are:
- A fun game to play.
- Child friendly controls.
- Large buttons and clickable areas for young fingers to operate.
- All game controls laid out together and in an intuitive way. 
- Fun images and sounds. 
- Visual and audio rewards while playing.

PicFlip! is a great way to help players meet these needs because:
- The planning and design process took all these needs into account before starting to build it. 
- Controls are grouped together clearly.
- Game controls are large, utilising icons and colours to communicate their purpose before any words that a child would not be able to read. 
- PicFlip! includes audio and visual rewards as part of the game.
- The overall feel of PicFLip! is fun and child-friendly.

#### Parental goals

Parents of pre-school children have a large amount of say about what games their children are exposed to, 
therefore parental needs must also be at the forefront of any project designed for children in this age group. 

Parent's goals are:
- A game with child development value. In this case to improve their memory and spatial awareness.
- Usability for the range of abilities in pre-school kids.
- A visually appealing, well-functioning game. 
- The ability for a parent to reset the stored player profile. 
- A mute button.

PicFlip! is a great way to help parents meet these needs because:
- PicFlip! gives a child a fun environment in which to practice their memory skills. 
- Game includes 3 levels of difficulty ranging from 8 to 16 cards.
- It has been designed with user experience as a priority, not only for a child using it but also for a parent.
- The game includes a reset data option, which is easy to find and operate by an adult who can read and do simple mathematics.

#### Developer and Business Goals

- Well thought out programming that prepares for a child's random and unpredictable use of PicFlip! 
For example, that the game cannot be broken by clicking many areas quickly, or if it is restarted at an unexpected moment. 
- A professional looking first dip into the world of using JavaScript, jQuery and Jasmine. 
- A project the developer is excited to make a part of her portfolio. 

#### User Stories

As a player aged between 1-5 years old, I want:
1. The ability to easily find and understand the controls for the game, so that I can operate them easily. 
2. A large easy to press buttons and controls, so that my young fingers can use on all devices.
3. Audio and/or visual feedback when I play the game, so that I know when I have clicked or not clicked something.
4. The ability to choose from cards with my favourite children’s characters on, so that I am even more engaged in finding them in the game.
5. Positive audio feedback when I complete a step in the game (for example when I find a matching pair of cards), because this increases my enjoyment from playing.
6. Visual icons and images that I recognise, so that I understand when I have achieved something in the game. For example stars out of five, and a trophy for high score.
7. The ability to see my old scores when I return to the game, so I can try to beat them.

As a parent of a player, I want:
1. Levels of difficulty for my child to choose from, so that they are engaged for longer and the game is useable for a wider age range.
2. A visually and operationally appealing game, so that I also have a positive experience when using it with my child.
3. The ability to delete a stored profile, so that I can reset the game for another go, or for another child. 
4. The option to delete a profile to be easy for me to find, but not easy for a child who is randomly pressing buttons to access, so that a profile is not deleted by accident.
5. A mute button to be included, so that the sounds can be switched off when they become annoying. (If only the actual child came with one of those too!).
6. To know who made the game and how I can contact them. 

### Design Choices

The overall feel of the game is one that is designed for children to enjoy. The following design choices were made with this in mind:

**Fonts**

- The primary font **Fredoka One** was chosen because it resembles the simple letters used in products made for pre-school children. It's likeness to fridge magnets for children is nostalgic for parents as well. 

- The secondary font **Bubblegum Sans** was chosen for its childlike qualities, while complementing the primary font nicely in style because it is more compact.

**Icons**

- All icons used were chosen for their obvious meaning and purpose so that they can be understood by everyone.

**Colours**

- The primary colour choices of dark and light blue for the logo, titles and text were chosen because they have a clean clear aspect while contrasting each other well.
- Other colours used in the project were taken from the trophy image sourced, using a colour picker in Photoshop to make sure all colours used were consistent across the entire project.

**Styling**

- Cards and container boxes were given rounded corners to continue the child friendly theme, many real life memory cards for children have corners like this. 
- Repeating the same rounded corner pattern throughout the page keeps consistency in design and maintains the feeling that all elements belong together. 

**Backgrounds**

- The background image of toy trains was chosen to give the feeling of playing the game in a child's playroom. 
- Specifically chosen because it is a "flat-lay" - a photograph taken from directly above - this means the background complements the game without distracting from it.
- The background images for the modals were chosen for their comic-book like qualities, adding a little positive emotional feedback at a level that appeals to a child. 

**Card images**

- Disney and Pixar characters were chosen for this game because they are recognised and loved by children. 
Cars characters were specifically chosen because it is extremely popular with boys, 
the Frozen characters because they are very popular with girls, 
and the Toy Story Characters because they appeal to both girls and boys. 

### Wireframes

These wireframes were created using [Balsamiq](https://balsamiq.com/) during the Scope Plane part of the design and planning process for this project. 

- [User info modal](https://i.ibb.co/FWBy68Q/Create-profile.png)
- [Game page](https://i.ibb.co/H2XtCW9/Game-page.png)
- [Win pop-up](https://i.ibb.co/5809P3Q/Win-popup.png)

## Features
 
### Existing Features

2. **Dashboard**
    - The game dashboard contains the player info display, difficulty selection, character selection, info, mute and reset buttons. 
    - On mobile devices a chevron arrow is displayed to tell the player to scroll downwards to the game board. 

5. **Character selection buttons**
    - Players can choose from three different Disney movie characters to display on the memory cards.
    - Selecting any of these buttons turns any face-up cards back over and reshuffles the cards.

6. **Mute button**
    - The mute button switches off all audio in the game. It is represented by a large speaker icon, which switches to one with a cross next to it when active.
 
7. **Reset button**
    - The reset button, represented by a curved arrow, resets the game, when it is pressed the game turns any face-up cards back over, reshuffles them and resets the turns counter back to 0. 
    - It does not reset the difficulty level or characters chosen for the cards. 

8. **Info button**
    - Represented by a large question mark, the info button opens the info modal. 
    - The info modal offers easy to understand instructions on how to play the game. 
    - Underneath how to play instructions there is information on how to open the modal to delete the player’s profile. 
    - The place to click is easy for an adult to see, but not an obvious button to click for a child. 

<div align="center">
<img src="https://i.ibb.co/xJ7PbS2/info-modal.jpg" alt="Screenshot: Info Modal" >
</div><br>

9. **Parental check modal**
    - This modal appears if the correct icon is clicked in the info modal. 
    - It explains that deleting the player profile will remove all game data including high scores. 
    - Then it asks a simple maths question with 9 possible answers to choose from, only if the correct answer is clicked will the player profile be deleted. 
    - All other choices will close the modal when clicked with no further effects to the game.
    - At this point the maths question and correct answer are static. This is a feature I would like to update in the future (see [Features Left to Implement](#Features-left-to-implement) for more information)

10. **Turns counter**
    - Located above the game cards, the turns counter counts the number of turns the player has taken in the current game. 
    - This total is then used to give the player a score out of 5 stars when the game is complete.

11. **Game board and cards**
    - The game board is where the memory cards are displayed. 
    - The cards are laid out in a grid 4 cards wide on medium to large screens, and 3 cards wide on phones to allow the size to remain easy for young fingers to tap on.
    - The number of rows of cards visible changes depending on the difficulty level selected. 

12. **Win modals** 
    - PicFlip! has two possible win modals that pop up when a game is completed. 
    - Both win modals display the number of stars the player won for the game they just played.
    - The standard win modal is launched if the player completed the game, but did not beat their previous high score.
    - The high score win modal is launched for a new high score, along with the number of stars earned the high score win modal also displays a trophy picture.


### Features Left to Implement

1. **Difficulty levels**
    - Add four different levels to the game for players to choose from. 
    - Easy (8 cards), Medium (12 cards), Hard (16 cards), and Expert (20 cards). 
    
2. **Theme selection**
    - Players can choose from three different Disney movie characters to display on the memory cards.
    - Selecting any of these buttons turns any face-up cards back over and reshuffles the cards.
    
3. **Player info modal** 
    - When playing the game for the first time, a modal pops up and asks for the players name.
    - The modal won't close unless the players name has been filled in. 
    - The modal is also activated if stored player data is reset.  
    
4. **Player info display**
    - At the top of the dashboard add the players name to be displayed. 
    - Underneath this add a display to show their highest score (out of 3 stars). 
    - The star display changes if a different level is selected. 
    


## Technologies Used

- This project uses HTML, CSS and JavaScript programming languages.
- [Gitpod](hhttps://www.gitpod.io/) 
    - Developer used **Gitpod** for their IDE while building the website.
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
- [Font Awesome](https://fontawesome.com/)
    - The project uses **Font Awesome** to provide icons for the memory game.
- [GitHub](https://github.com/)
    - This project uses **GitHub** to store and share all project code remotely. 
    
## Testing 

The HTML and CSS code was validated using the W3C validator. It had no errors or warnings to show. The website was examined in both
Chrome and Safari to check for cross brower compatibility. The responsive design mode was used in both browsers to examine the site 
at various screen sizes. The site was viewed in both Chrome and Safari on the following devices:

- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5/SE
- iPhone 6/7/8
- iPhone 6/7/8 plus
- iPhone X
- iPad
- iPad Pro
- Laptop screen

I played the memory game to ensure that it worked as it was supposed to. 
I clicked on the 'play again' button to ensure the game restarted once clicked on.

## Deployment
 
This project was developed using [Gitpod](https://www.gitpod.io/), committed to git, pushed to GitHub, and deployed via GitHub pages.  

## Credits

### Content

- The text from the memory game was copied from [Scotch](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript)
- The text from the README.md file was copied from [Picflip!](https://github.com/AJGreaves/picflip)

### Media

#### Images

- The background image for my memory game was taken from [Wallpaper Abyss](https://wall.alphacoders.com/by_sub_category.php?id=152813&name=Halloween+Wallpapers)
- The icons for my card deck were taken from [Font Awesome](https://fontawesome.com/icons?d=gallery&c=halloween&m=free)

### Code

- The code for my memory game was taken from [Scotch](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript)

### Acknowledgements

Special thanks to:
- Code Institute tutors for helping support and guide me in the right direction with my code. 

Many thanks! Michelle

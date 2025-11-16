Project Description: 
This project is a simple Thanksgiving-themed emoji memory game built with SwiftUI. 
The goal is to match the cards that show the same two Thanksgiving emojis, like a turkey, corn, maple leaf, leaves, pumpkin pie, and a turkey leg.
The app uses an MVVM Architecture:
- Model that handles the game data and matches
- ViewModel, which creates the cards, shuffles them, and connects the model to viewing.
- View that shows the grid and layout of the cards, title, and the new game button.

Project Features:
- Thanksgiving theme using the emojis for representation, with orange and brown colors for the background.

MVVM Architecture
- MemoryGame handles the card matching, GameViewModel shows the list of cards, and functions like choose(card).

Card Flip Animation
- Cards use a 3D flip effect when they turn face up or down
- The flip works using changes to 'isFaceUp', 'rotation3DEffect', and 'animation'

New Game Shuffle Animation
- Pressing the 'New Game' button will shuffle the cards, and you can do this as many times as you want

UI Layout
- Simple layout with title, emoji card grid, and New Game button.
- Uses warm Thanksgiving colors in a holiday theme.

Here are our video recordings that explain how the app works:

MVVM Architecture Aleks Lubczynski
https://youtu.be/aPxfPm39IDU 

Transition/Animation Ian Mackenzie

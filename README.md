# Chess application

This is interactive chess application for two-players. It is responsive and implements all features of real chess. Click [**here**](https://kbonna.github.io/chess-app-plain-js/) to play!

## Application features

1. Interactive chessboard with movement checking and board highlighting. 
2. Two players (no single-player mode)
3. All chess moves available including:
	- capturing enemy pieces
	- castling
	- *en passant*
4. Check and checkmate detection with UI warnings.
5. Interactive promotion panel.
6. Side control panel.
7. Timer with different time settings and start / pause button.
8. Side switching and game reset.
9. Automatic blocking after finished game.


## Used Technologies

Game was created using only:

- vanilla JS
- HTML 
- CSS

Sass preprocessor and BEM naming convention was used for CSS. Object oriented approach was used for JS with separate classes for chess logic, timer and UI. Chess class is well tested using `jest`, with most important parts documented using `jsdoc` scheme. This project was created as a learning experience with JavaScript.

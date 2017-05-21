# Android-Chess-Application
Basic 1v1 Chess Application for Android Mobile


#Design
Exercises basic software design patterns to create a two player chess application.
Graphical user interface allows for several features:
  - highlights the piece that was selected
  - highlights the king when he is in check
  - allows for unlimited undos
  - saves and reloads the game state with fragment life cycle management
  - reset button
  
#Results
Pretty much fully functional.
Current edgecase bug with detecting check mate situtations, caused by an interaction with the enemy pawn.

![alt text](https://github.com/h397wang/Android-Chess-Application/blob/master/Screenshot_2016-11-06-20-57-04.png)
![alt text](https://github.com/h397wang/Android-Chess-Application/blob/master/Screenshot_2016-11-06-20-57-40.png)
![alt text](https://github.com/h397wang/Android-Chess-Application/blob/master/Screenshot_2016-11-06-20-58-06.png)
![alt text](https://github.com/h397wang/Android-Chess-Application/blob/master/Screenshot_2016-11-06-20-58-12.png)


#Hindsight
There was a lot of code repetition involved for the various types of chess pieces. A better use of inheritence would remove this effort.
Toast messages could be more specific to indicate the type of error.
Edge cases can probably be handled in a neater fashion, currently kind of a spaghetti monster.
Good exercise for a first large scale coding project. 

#Extensibility
Highlight tiles available tiles where the current piece can move
Create a single player mode with a pseudo AI

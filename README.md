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
Currently has issues with detecting check mate situtations - most likely source of error is interaction with the pawns.
However since the user has the option to reset, if the kind isn't actually in check mate the game can just keep going :3

#Hindsight
The factory method is probably being abused here, probably a more efficient way to work with the different chess pieces.
Toast messages could be more specific to indicate the type of error.
Edge cases can probably be handled in a neater fashion, currently kind of a spaghetti monster.
Good exercise for a first large scale coding project. 

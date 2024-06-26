# AspireNex Insternship Tasks (AI Internship)

### 1. Task 1:- TIC-TAC-TOE AI
   ##### 
   1. The main key functions used in code are:

      a. ```gameBoard()``` - Prints the current state of the board

      b. ```boardFull()``` - Checks if the board is full (no more empty spaces)

      c. ```winningPlayer()``` - Checks if a player has won by checking all possible winning combinations

      d. ```getScore()``` - Returns a score of 1 if X wins, -1 if O wins, 0 for tie

      e. ```alphaBeta()``` - Implements minimax with alpha-beta pruning to determine best move

      f. ```computerMove()``` - Uses alphaBeta to determine the best move for the AI player and make the move

      g. ```playerMove()``` - Gets input from the human player and makes their move

      h. ```play()``` - Main game loop, calls the other functions to alternate moves between AI and human players until game over

### 
 2. Instructions to play:
 
  To play the game first, we should call play() function. This game requires 2 players. By default player1 will be our AI agent i.e , x_player and player2 will be user i.e, o_player can be random.
  
  Alpha-Beta pruning improves efficiency greatly by pruning branches that doesn't need to be searched.
  
  This allows our AI agent to play perfectly and never lose a game.

### 2. Task 2:- CHATBOT WITH RULE-BASED RESPONSES
   ####
   Steps:-
   ######
   1. Import the necessary libraries:-
         ```
         from nltk.chat.util import Chat, reflections
         ```
   2. Define Pairs:-

   The `pairs` variable contains a list of patterns and responses. Each pattern is a regex pattern that matches user inputs. The chatbot responds with one of the             corresponding responses.`

   3. Define Reflections:

   The `reflections` dictionary contains a set of input transformations. For example, it maps "I am" to "you are".

   4. Create and Start the Chat:
```
chat = Chat(pairs, reflections)
chat.converse()
```



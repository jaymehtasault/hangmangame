# hangmangame
use of ai : used chatgpt for refrence used in this code 
void _startNewGame() {
    setState(() {
      _wordToGuess = _words[Random().nextInt(_words.length)];
      _guessedLetters.clear();
      _wrongGuesses = 0;
      _gameOver = false;
      _playerWon = false;
      _controller.forward(from: 0);
      _confettiController.stop();
    });

    used gpt to match and to get littlebit of idea and matched with my code for refrence 
    used to add emoji for animation.

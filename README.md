# Celo---Jackpot-game

Key Features:

Points System: Players earn and spend points instead of cryptocurrency
Game Lifecycle:

Owner starts a new game
Players enter by spending points (entry fee)
Owner draws a winner when minimum players are reached
Winner receives all accumulated points


Main Functions:

awardPoints() - Owner gives points to players
startNewGame() - Begins a new jackpot round
enterGame() - Players join with their points
drawWinner() - Randomly selects a winner
Various view functions to check game status and player points


Safety Features:

Only owner can start games and award points
Players can only enter once per game
Minimum player requirement before drawing winner
Prevents entering finished or inactive games



Note: The random number generation uses block data (timestamp, prevrandao) which is fine for a points-based game, but would NOT be secure for real funds as it could be manipulated by miners/validators.
The contract is completely fund-free - no ETH or tokens are handled, only internal point tracking!RetryClaude can make mistakes. Please double-check responses.

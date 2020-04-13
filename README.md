# chess-system
### Chess Game System made in Java to run in terminal.

## **Initial Instruction**
Clone or Download the program and setup colours in your terminal to easy the distinction of the pieces. Below, you will find links to get easily the configuration of your terminal color.

- Windows: https://github.com/git-for-windows/git/releases/tag/v2.26.0.windows.1
- OSX: https://stackoverflow.com/questions/1550288/os-x-terminal-colors

## **Executing The Game**
Para executar o jogo via terminal, deve-se ir até a localização do programa e acessar a pasta bin. Para iniciar o Jogo, digite: 
To run the game through the terminal, you must go in the program location that you cloned/download and access the Bin folder. To start, just type:

``` java application/Program ```

The board is presented with the pieces already positioned, ready to play. Following the rules, the white piece starts the game. You can finish the execution of the game pressing *control + c* or *CTRL + c* from your keyboard in the terminal.

## **The Pieces**
Each opponent has 8 pawns, 2 rooks, 2 knights, 2 bishops, a king and a queen.

In the board you will find these pieces with the following letters:
- R = Rook
- N = Knight
- B = Bishop
- Q = Queen
- K = King 
- P = Pawn

## **King**
The King can move only one and any position to each side. Except by the Castling Kingside, when the kings move two position to the Rook’s direction and the Rook step by side the king. It’s not allowed two kings stay side by side each-other, it must to have at least one position between the kings.

The king is the only piece that can not be captured. When the king is attacked, it will happen a xeque and he is forced to leave xeque situation. There’s 3 alternatives to leave xeque.

1 - Move a position that aren’t receiving an attack;
2 - Capture the piece that are putting him in xeque;
3 - Put a piece covering the king from an attack in xeque.

**Obs¹**: When xeque is being applied by knight, this third option it doesn’t work, because the knight has the ability to jump other pieces;
**Obs²**: When the king can’t get away from xeque, he is up to Xeque-Mate, then the opponent wins the game. Once the goal of the game is just this: Apply the Xeque-Mate.

## **Queen**
The Queen can do the same King’s move, having only one difference. It can be move to all directions, any position wanted. The queen can do the Rook and Bishop move, this mean, move in horizontal, vertical (like Rook) and in the diagonal (like Bishop). 

## **Rook**
The Rook can move in the vertical and horizontal.

## **Bishop**
The Bishop move in the diagonal. The white bishops pieces, move in the diagonal of white position and the black bishops pieces, move in the diagonal black position.

## **Knight**
The Knights move a position and the other in the diagonal, making a L form. Or two position to a side one to another, as you wish. It’s the only piece that can jump another piece. The only way to leave Xeque from Knight is capturing this piece or moving the King.

## **Pawn**
The Pawns can move one step forward, and capture a piece moving in the diagonal. In the first move of each pawn, it can be moved one or two positions ahead.

- En Passant move: When a pawn is in the fifth position and the opponent move two position ahead, the pawn of fifth position can capture it, moving the piece to the empty position (move pass) from the second pawn, moving in diagonal position. This action can be executed in the next turn after the second pawn move.

- Promotion move: It’s when a pawn cross the eighth position, and get a promotion to be replaced by a special piece (Queen, Knight, Bishop or a Rook), except the King. It’s possible have more than one Queen.

- Big Castling: The King move two position at Queen’s side and the Rook stay at King’s side.

- Small Castling: The King move two position at Rook’s side and the rook stay at King’s side.

Obs¹: The king can’t be moved in the match and can’t be in Xeque;
Obs²: Can’t have any piece between the King and Rook, that can’t be moved until the Castling;
Obs³: It can have any position being attacked between the Rook and King.

## **Xeque**
When the king is being attacked, we assume the Xeque. The king is the only piece that can’t be captured. So, when the king is in Xeque, he is obliged toe leave the attack position. Moving out, capturing the piece that is attacking or intercepting the attack, moving a piece forward of the King.

## **Xeque-Mate**
When the King is unable to escape from Xeque, we assume the Xeque-Mate. Right now, this match is over having winning the opponent player.

## **Draw**
There’s a few situation where no opponent wins and draw the match.

- When the King is “drawn”, it means, that the next turn be none of the pieces in board can be moved, including the King, because for this, any move performed put in Xeque; 

- When remain only two kings in the board;

- After 50 move without any piece be captured or pawn move. This count can be started, but, always that happens a piece captured and a pawn be moved, the count starts over.

### Have fun!

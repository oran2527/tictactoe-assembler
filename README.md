# TICTACTOE ASSEMBLER

## LANGUAGE

Assembler

## HOW TO RUN 

1. In the shell inside the folder with the tictactoe.asm file, type : nasm -f elf64 tictactoe.asm

2. In the same shell, type ld -o tictactoe tictactoe.o

3. In the same shell, type ./tictactoe

4. Start to play

## ALGORITHM

A board with 9 positions and the first player will mark a "X" and the second player marks and "O". The players don't play an occupied position. 

The player wins if you complete the consecutives XXX or OOO horizontal, vertical or diagonal.

## USER FLOW

The user must type the number of the board in the following positions :

1 2 3

4 5 6

7 8 9

The system displays a board and starts with the first player selecting a position inside the board. The player must mark empty positions.

The player must type the number and press enter

## PIECES OF CODE

main_loop: --- > Main page that iterates until the player wins or tie according with our game

call clear_screen --- > Clear the screen
        
mov rsi, game_start_message --- > Put the message "game_start_mesage"

## SCREENSHOT

![image 1](https://github.com/oran2527/tictactoe-assembler/img/asm1.JPG)

![image 2](https://github.com/oran2527/tictactoe-assembler/img/asm2.JPG)

![image 3](https://github.com/oran2527/tictactoe-assembler/img/asm3.JPG)

![image 4](https://github.com/oran2527/tictactoe-assembler/img/asm4.JPG)

![image 5](https://github.com/oran2527/tictactoe-assembler/img/asm5.JPG)

![image 6](https://github.com/oran2527/tictactoe-assembler/img/asm6.jgp)

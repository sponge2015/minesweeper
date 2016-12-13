# minesweeper 
This project is for minesweeper game. Firstly, I create a 9x9 field indicating the game field. 
Secondly I set all the field with -1 indicating field that had not been clicked.
Then I generates random number and set mines where number is 9. 
Then calaulate number of mine around a coordinate being clicked and print.
It calculates the number of mines and when the user click all the coordinate without mine, the user wins.
If user click a blank field, it will enlarge the field with 3x3 field in center of blank coordinate. 
you can compile with 'g++ -o sweep minesweeper.cpp' and then './sweep'

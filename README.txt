sudoku

Here I have created a program which will solve any solvable sudoku puzzle.

The programme accepts arguments in the command line and will solve the puzzle and print the result to the terminal. If there is an error in input or the puzzle cannot be completed then an error message will be printed. 

Here is an example

go run . ".96.4...1" "1...6...4" "5.481.39." "..795..43" ".3..8...." "4.5.23.18" ".1.63..59" ".59.7.83." "..359...7"
3 9 6 2 4 5 7 8 1
1 7 8 3 6 9 5 2 4
5 2 4 8 1 7 3 9 6
2 8 7 9 5 1 6 4 3
9 3 1 4 8 6 2 7 5
4 6 5 7 2 3 9 1 8
7 1 2 6 3 8 4 5 9
6 5 9 1 7 4 8 3 2
8 4 3 5 9 2 1 6 7

Below are some example tests to be pasted one at a time into the terminal. Each will result in a completed grid similar to what is shown above.

go run . "1.58.2..." ".9..764.5" "2..4..819" ".19..73.6" "762.83.9." "....61.5." "..76...3." "43..2.5.1" "6..3.89.."
go run . "..5.3..81" "9.285..6." "6....4.5." "..74.283." "34976...5" "..83..49." "15..87..2" ".9....6.." ".26.495.3"
go run . "34.91..2." ".96.8..41" "..8.2..7." ".6..57.39" "1.2.6.7.." "97..3..64" "45.2.8..6" ".8..9..5." "6.3..189."
go run . "..73..4.5" "....2.9.." "253.6487." ".9.74.36." "....3..8." "8362.9.47" "1..8.26.3" "6......18" ".8261...4"
go run . "935..7..8" "...3.8.7." "6..5..49." ".73..4..." "4..175.8." ".618..247" ".187....." "..6.8.75." "75.4.3862"
go run . "..5.2...1" ".8735..46" "4...6.5.." ".5.9....." ".7..3541." "69314.857" "7415..6.8" "...284..5" "5.....3.4"
go run . "..75...3." "8..23...9" ".3479.86." "..3..4198" ".4815...3" "..6.23..7" "351.6.78." "4..31...6" ".7...5..2"
go run . "53..7...." "6..195..." ".98....6." "8...6...3" "4..8.3..1" "7...2...6" ".6....28." "...419..5" "....8..79"
go run . ".58..4.21" ".6.853..7" ".39.2...5" "8....1..6" "..37..21." "1.6.825.." "67.2..18." "9..4...5." ".8.9167.2"
go run . "71.4.9..2" ".8.5....." "9...3..1." "839..21.4" "..7.4.2.." "4.13..795" ".5..7...8" ".....5.3." "6..1.3.47"

Below are some example tests to be pasted one at a time into the terminal. Each are invalid and will result in "Error" being printed to the terminal.

go run . ".932..8." "27.3.85.." ".8.73.254" "9758...31" "....74.6." "6.45.38.7" "7....2.48" "32.4...7." "..8.579.."
go run . ".867.2..4" ".2.5..8.." "154.9.237" ".7.9.5..1" ".29..4.18" "51.6...42" "2.5.7..83" "...153..." "39...8.75"
go run . ".7....28." ".2...6.57" "8654729.." "..925..64" ".4..19.7." "7.8..4..9" "3..7..698" "..79.1..." "59..28.39"
go run . "..213.748" "8.4.....2" ".178.26.." ".68.9.27." ".932....4" "5..46.3.." "..9.24.23" "..63..19." "385..1.2."
go run . "9.46.3..1" "37.1..2.6" "..6..93.4" "..13..9.5" "56..91..." "82...461." "..79...4." "425.167.." "1.2..75.8"
go run . "not" "a" "sudoku"
go run . "53..8294." "8..34...5" "3542761.." "..6.3...4" "9....162." ".9...3.78" "7438.9..." "..5..43.1"


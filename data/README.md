# Cumulative cultural evolution without copying in children and Baboons

This repository contains the experimental data files for the manuscript "High-fidelity copying is not the key to cumulative cultural evolution: A study in monkeys and children" by Saldana, Fagot, Kirby, Smith and Claidiere (2018).

`dataChildren.csv` and `dataBaboons.csv` contain the data sets for the children and baboons experiments respectively. The `responsePatterns` folder contains the visualisations of the response grid patterns.

### Descriptions of the column headings for each .csv data file are as follows: 

- `GridSeen` : input pattern
- `GridDone` : output pattern
- `Generation` : generation number within the transmission chain
- `TrialNumber` : trial number
- `DateTime` : date and time stamp for the trial
- `ChainNb` : transmission chain number 
- `TetrominoDone` : tetromino type produced (`None` if the patterns produced is not a tetromino shape)
- `BinTetroDone` : presence  or absence of a tetromino shape in output 
- `TopBottomDone` : top/bottom position of the produced pattern (`Und` if undefined, i.e., if it is not in the top or bottom half of the grid, but in the middle)
- `RightLeftDone` : same as above but with the right/left halves of the grid
- `TetrominoSeen` :  tetromino type of input pattern (`None` if not a tetromino shape)
- `BinTetroSeen`: presence  or absence of a tetromino shape in input
- `TopBottomDone` : top/bottom position of the input pattern
- `RightLeftSeen` : same as above but with the right/left halves of the grid
- `Score` :  successful and unsuccessful trial
- `Symmetry` :  `Vert`, `Horiz`, `None` for vertical (top vs bottom), horizontal (right vs left) or no opposite-side grid responses respectively
- `SymmetryBin` : presence or absence of opposite-side grid responses
- `TrialName` :  trial ID 


#### Specific columns headings for `dataChildren.csv`  are as follow:

- `PartID` : participant ID number
- `PreviousPartID` : ID number of the parent participant, from whom data is used as input


#### Specific columns headings for `dataBaboons.csv`  are as follow:

- `Name` : the baboon’s name
- `Sex` :  the baboon’s biological sex
- `Age` : the baboon’s age in months
- `TestingPhase` :  `Test` or `Random` depending on the test trial type

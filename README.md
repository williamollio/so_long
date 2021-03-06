# 42 So_long

<strong>Summary</strong>

This project’s objectives are similar to all this first year’s objectives: Rigor, use of C, use of basic algorithms, information research etc.
As a graphic design project, so long will enable you to improve your skills in these areas: windows, colors, events, textures, etc.

![so_long](https://github.com/williamollio/so_long/blob/master/gif/so_long.gif)

[Subject PDF](https://github.com/williamollio/so_long/blob/master/subject/so_long.pdf)

# Clone
Open a terminal and run following command:
```
git clone <repository url>
```
# Run
Go to the created repository and run following command:
```
make
```
To start run following command :
```
./so_long ./maps/<map choosed>
```
# Gameplay


Eat all the collectables with by controlling the figuring. When all the items are eaten, the exit door can be reach and the game is over.

| Keys | Move |
| :--- | :--- |
| A | left |
| S | down |
| D | right |
| W | up |
| esc | exit |


# Explanations

Here is an example of a valid map (format expected .ber) to launch and play the game :
```
1111111111111111111111111111111111
1E0000000000000C00000C000000000001
1010010100100000101001000000010101
1010010010101010001001000000010101
1P0000000C00C0000000000000000000C1
1111111111111111111111111111111111
```

- <strong>1 </strong> : Walls
- <strong>E </strong> : Exit
- <strong>P </strong> : Player
- <strong>C </strong> : Collectables
- <strong>0 </strong> : Floors

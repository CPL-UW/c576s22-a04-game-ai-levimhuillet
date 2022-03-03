# CS576-Tetris-Sample

1. Clone this repo
2. Open it in a 2021 version of Unity
3. 2xClick TetrisScene (in Assets/Scenes)
4. Hit run?

Apologies for the mess. YMMV.

Levi's AI modifications:

 - AI now checks AI_DEPTH number of moves ahead when evaluating a best score (curently set to 4).
 - AI also generates a list of columns with the shortest height, randomly selects one,
and assigns a higher score to piece moves that move closer on the x-axis towards that column.

Build for Windows is located in Builds/
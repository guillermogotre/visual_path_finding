# visual_path_finding
Simple Python path-finding program for teaching. The player can only go forward or turn right.

## Pending optimizations
- _Don't add already closed nodes to the_ ```frontier``` _on node expansion_.
- _Check if the expanded node is the same as the ```target``` on node expansion_.

## How to use
- Left-click: 
    1. Player
    2. Target
    3. Walls
- Right-click:
    - Erase
- Keys:
    - ```R```: Rotate player
    - ```F```: Forward player
    - ```C```: Clear game
    - ```1```: BFS
    - ```2```: Dijkstra
    - ```3```: A-Start


## Color-coding
- Red: Player
- Purple: Target
- Black: Wall
- Blue: Closed nodes
- Green: Open nodes
- Orange: Plan steps

## Screenshot
![A-Star Screenshot](images/screenshot.png)
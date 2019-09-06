# Split Flap

![gif](images/splitFlap.gif)

## UI

### Basic Usage
Enter the data directly into the UI window's table. Accepted characters are: A-Z, 0-9, and special characters: space, colon, forward slash, period. Choosing other characters besides these currently ends up glitching the whole board, so don't do it. You can navigate the table with arrow keys, tab key or mouse clicks.

When finished entering the data you can click the "Commit" button. The button will turn red. Wait until the red turns off to commit new changes.

Each section only allows a certain amount of characters:
Platform: 2, Name: 20, Time: 5, Status: 7

The color section allows characters to show up as white or yellow or red. Enter w, y, r or b respectively to do so.

The order section works with the "Reorder" button. To switch data from one row to another, switch the order numbers. Ex. if you want the data on row eight to appear in row nine, change row eight's order number to 9 and row nine's order number to 8, hit the "Reorder" button and then hit the "Commit" to confirm the change.

The blink section controls whether the row blinks or not. Put a 1 in the cell to turn on blinking, otherwise leave it blank.

### Other Parameters
#### Flip
Time Method: Choose either between having them flip at a certain "Speed" (and they'll reach their destination at different times), or choose them to flip over a certain "Duration" (and they'll flip at different speeds)

Time: Either the flip velocity if "Speed" is chosen, or amount of time it takes for it to reach it's final character if "Duration" is chosen.

Speed Smoothing: Ease In/Out (acceleration/deceleration) function for the flipping when "Speed" is chosen. Real split flaps displays normally don't have this, but it does give the digital version a nice effect visually and helps break up the sound a bit.

Audio: Toggle for turning on/off a clacking sound. I've included the Ableton project with the source files in case the sound needs to be tweaked.

Trigger Threshold: This determines at which part of the spin animation [0 to 1] does the clack sound get triggered.

#### Titles
Enter in anything you want for the headers/titles.

#### Colors
Change the colors of the headers/titles/board. Also can change the angle and strength of the light (there are shadows for the headers/titles)
![params](images/params.png)

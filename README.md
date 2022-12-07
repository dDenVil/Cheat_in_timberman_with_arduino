## Cheating in the game "Timberman" with help of Arduino Pro Micro

I made this 3 years ago, so don't harshly. The rules of this game are simple, chop the log of tree from the left or right side. Accordingly press the buttons A or D, but be careful don't get stunned by branch = lose. Is has the scale that act like timer, so you have to press buttons fast to refill it, other way you lost.
![in-game](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/intro.jpg?raw=true)
I've used the same [device as for cheating in the "Intralism"](https://github.com/dDenVil/Cheating_in_Intralism_with_Arduino). Based on 4 photoresistor, 8 resistors, 1 button, 3 LED's and Arduino Pro Micro that can simulate keyboard or mouse.
##Why do I need this
- It is fun;
- You can unlock almost all skins for timberman;
- First in the leaderboard of the game;
- To be the god in the multiplayer mode.

## Getting started
As I said, I have used previously made [device board](https://github.com/dDenVil/Cheating_in_Intralism_with_Arduino/blob/main/Readme_assets/board.jpg?raw=true). I just had to make slight code changes.
This game require only 2 photoresistors. Button is made for easy start, and LED's are showing what button was pressed.

![scheme](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/sheme.jpg?raw=true)
>Schemetics

[Code](code.txt) is such a mess. Now I am looking at this and can't understand why it worked. How the hell did it work. Algorithm is the next:
- Including "Keyboard.h" library;
- reading value from button to start/stop and blinking with yellow led;
- reading values from sensors;
- pressing correspond button.

## Results

Achieved [score](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/top.jpg?raw=true) of 4141 choped logs. That is really high. And got a lot of new
[skins](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/skin.jpg?raw=true) . Here some old videos (gifs):

![gif2](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/gif2.gif?raw=true)
![gif1](https://github.com/dDenVil/Cheat_in_timberman_with_arduino/blob/main/gif1.gif?raw=true)


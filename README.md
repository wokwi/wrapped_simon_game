![](../../workflows/multi_tool/badge.svg)

# Simon Says Game

Simon is a simple electronic memory game: the user has to repeat a growing sequence of colors. The sequence is displayed by lighting up the LEDs. Each color also has a corresponding tone.

In each turn, the game will play the sequence, and then wait for the user to repeat the sequence by pressing the buttons according to the color sequence. If the user repeated the sequence correctly, the game will play a "leveling-up" sound, add a new color at the end of the sequence, and move to the next turn.

The game continues until the user has made a mistake. Then a game over sound is played, and the game restarts.

Simulate this project on Wokwi: https://wokwi.com/projects/352319274216569857

[![Simon Says Game](docs/simon_game.png)](https://wokwi.com/projects/352319274216569857)

## Pinout

| Pin | Direction | Function             |
| --- | --------- | -------------------- |
| 8   | Input     | Button 1             |
| 9   | Input     | Button 2             |
| 10  | Input     | Button 3             |
| 11  | Input     | Button 4             |
| 12  | Output    | LED 1                |
| 13  | Output    | LED 2                |
| 14  | Output    | LED 3                |
| 15  | Output    | LED 4                |
| 16  | Output    | Speaker/Buzzer (PWM) |
| 17  | Input     | Reset                |

# Zero to ASIC Course

This project was made as part of the [Zero to ASIC Course](https://zerotoasiccourse.com)!

# License

This project is [licensed under Apache 2](LICENSE)

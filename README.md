# Python Games

Two small games from my early Python projects.

## Hangman (`hangman/`)

![Hangman stages](docs/hangman_stages.png)

*The stick-man stages used by the game.*


A Hangman game with a dark CustomTkinter interface. It picks a random word from a list of about 100 words (Whisper, Quantum, Labyrinth and so on), and each wrong guess draws the next stage of the stick man. The game has replay and quit buttons.

```bash
pip install customtkinter pillow
cd hangman
python hang_man.py
```

Run it from inside the `hangman/` folder because the images are loaded by relative path.

## Flappy Bird (`flappy_bird/`)

A Flappy Bird clone with no game engine. OpenCV draws the bird and pillars onto a NumPy canvas each frame, and the `keyboard` library reads the keys: **Space** to flap, **R** to restart.

```bash
pip install opencv-python numpy keyboard
cd flappy_bird
python Flappy_bird.py
```

On Windows the `keyboard` library needs no extra setup. On Linux it needs root.

## Related
Controlling games with a webcam: [Gesture-Gamepad](https://github.com/Shaikh-Mohammad-Hasnat/Gesture-Gamepad).

## Author
Shaikh Mohammad Hasnat, [GitHub](https://github.com/Shaikh-Mohammad-Hasnat), [LinkedIn](https://www.linkedin.com/in/shaikh-mohammad-hasnat-698a08335)

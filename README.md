
# SIMPLE BEEP!

Simple beeping program written in python for all cross-platforms




## Features

- Simple and Clear
- Cross platform


## Installation

For cross-platforms
```bash
  pip install beepy
  pip install simpleaudio
```

For Mac

```bash
  pip install -U PyObjC
```

With Pygame

```bash
    pip install pygame
```

For Windows
    
    #comes In-built

    
## Code

Winsound

```python
import winsound
winsound.Beep(440, 500)
```

Pygame

```python
from pygame import mixer
mixer.init() 
sound=mixer.Sound("bell.wav")

sound.play()
```

Simpleaudio

```python
import simpleaudio 

wave_obj = simpleaudio.WaveObject.from_wave_file("bell.wav")
play_obj = wave_obj.play()
play_obj.wait_done()
```

Beepy

```python
import beepy

beep(sound="ping")
```

AppKit

```python
import AppKit

AppKit.NSBeep()
```
## Acknowledgements

 - [AppKit](https://developer.apple.com/documentation/appkit/)
 - [Winsound](https://docs.python.org/3/library/winsound.html)
 - [Beepy](https://pypi.org/project/beepy)
 - [Pygame](https://www.pygame.org/)
 - [SimpleAudio](https://simpleaudio.readthedocs.io/en/latest/)


## License

[MIT](https://github.com/hack505/Simple_beep/blob/main/LICENSE)

## Authors

- [Hack505](https://www.github.com/hack505)

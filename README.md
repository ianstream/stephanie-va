Stephanie
=============

Stephanie is an open-source platform built specifically for voice-controlled applications as well as
to automate daily tasks imitating much of a virtual assistant's work.

To learn more, head to [Stephanie](http://slapbot.github.io/), which has nicely formatted guides for installation, configuration, usages, etc. along with the extensive documentation.

## Getting Started

**Linux**

- Install portaudio: `sudo apt-get install portaudio19-dev`
- Install python (2 or 3)
- Install python pip: `sudo apt-get install python-pip` or `sudo apt-get install python3-pip`
- Install required libraries `python install.py` or `python3 install.py`
- Add API keys to `config.ini`
- Run `python Index.py` or `python3 Index.py`

## Support

If you run into an issue or require technical support, please first look through the closed and open **[GitHub Issues](https://github.com/slapbot/stephanie-va/issues)**, as you may find a solution there (or some useful advice, at least).

If you're still having trouble, the next place to look would be the new [Subreddit Stephanie](https://www.reddit.com/r/StephanieAssistant), as well as [Quora Stephanie](https://www.quora.com/topic/Stephanie-Virtual-Assistant). If your problem even still remains unsolved, contact me personally through a message on any of social networks like [facebook](https://www.facebook.com/Drazier), [Quora](https://www.quora.com/profile/Ujjwal-Gupta-31), [Reddit](http://www.reddit.com/user/drazxie). (Not too sure about facebook because of their spam filter, so consider quora or reddit as first choice.)

## Contact

If you are looking for just a casual conversation about Stephanie or anything related to bugs/feedback or just anything, contact me through social network links like [facebook](https://www.facebook.com/Drazier), [Quora](https://www.quora.com/profile/Ujjwal-Gupta-31), [Reddit](http://reddit.com/user/drazxie), whereas for any formal enquiries or serious discussion consider dropping me a mail at ugupta41@gmail.com

## Sounder Algorithm

The brain of the Stephanie is an algorithm which predicts the intent through a speech converted text, to know more about it's internal API and the algorithm itself check the paper and the library present here at [Sounder](https://github.com/slapbot/sounder) which is completely open-source.

## 3rd Party Modules

Created your very own 3rd Party Module and want to share it with the community? Share it here at [Subreddit Stephanie](https://www.reddit.com/r/StephanieAssistant) so that we could verify it as legit and showcase it in our main website.

## License

*Copyright (c) 2017 Ujjwal Gupta. All rights reserved.*

Stephanie is covered by the MIT license, a permissive free software license that lets you do anything you want with the source code, as long as you provide back attribution and ["don't hold \[us\] liable"](http://choosealicense.com). For the full license text see the [LICENSE.md](LICENSE.md) file.

As well as I am not accounted for any 3rd Party Module Installations, so make sure they are legit before installing it, as I will not be liable for any kind of damage in terms of virus/data leak or whatnot.

## install exception

If you get error..
- when '#include "portaudio.h" file not found' error, install portaudio.
- when '#include "SDL.h" file not found' error, install sdl sdl_image sdl_mixer sdl_ttf portmidi.

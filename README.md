# Kesha v3.1 very early (aka Jarvis update)
Simple Voice Assistant made as an experiment using [Silero](https://github.com/snakers4/silero-models) & [Vosk](https://pypi.org/project/vosk/).
<br>Later on [Picovoice Porcupine Wake Word Detection](https://picovoice.ai/platform/porcupine/)

![image](https://images.unsplash.com/photo-1578632749014-ca77efd052eb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80)

`The code has NOT been polished and is provided "as is". There are a lot of code that are redundant and there are tons of improvements that can be made.`

# Installation
First, install the requirements, the `requirements.txt` file is just an output of `pip freeze` from my test venv 'k.<br>
Second, check `config.py` and set required values (api key, device index).<br>
Next, run the `main.py` script and Voilà, as simple as that.<br><br>

And don't forget to put models of Vosk to main folder.<br>
You can get the latest from the [official website.](https://alphacephei.com/vosk/models)
<br>The one I was using is `small`.
<br>p.s. If you don't understand how to install or where to put the Vosk model, I've made a [screenshot](https://i.imgur.com/N3bu2lC.png) for you.

# Python version
I was using Python `3.10.1`, but it should work on any newer version.

# Author
(2022) Abraham Tugalov, YarBurArt

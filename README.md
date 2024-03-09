# SM64 Practice Script (very barebones!)

![SM64Prac](https://i.imgur.com/90A65mj.gif)

## Getting Started - Basic (.exe)
(Windows) Download the latest .exe from Releases on the right sidebar, and then run it. If SmartScreen shows a warning about untrusted software, this can be ignored. Keep in mind that .exe versions of this will have the weighting and star choice per category hard locked, since this script doesn't currently have a built in feature to edit weighting/choice of stars.

## Getting Started - Advanced (.py)
Otherwise, if you want to edit the script (e.g. fine tuning the weighting of the stars to your specific needs, swapping out stars in certain categories), or are using a different operating system, you can find the Python script itself included with each release. You can also use the 'sm64.py' file that will recieve commits between releases. The steps below are based on the file being named this, here is how to run it from scratch:

Download the Python 3.11.6 version best suited for your OS here, if you don't currently have it installed: https://www.python.org/downloads/release/python-3116/

Next, follow the instructions listed below for your OS. Keep in mind this is assuming that Python is installed in PATH, and that py commands will point to Python 3.11.6.
#### Windows:
1. Open command prompt (cmd.exe)
2. Enter this exact command: "py -m pip install colorama pick py-getch"
3. Download the 'sm64.py' script, and navigate to the folder it downloaded to
4. Run the 'sm64.py' script
#### Linux:
1. Open your terminal
2. Enter this exact command: "pip3 install colorama pick py-getch"
3. Download the 'sm64.py' script, and navigate to the folder it downloaded to
4. Change the properties of the 'sm64.py' so it can be executed
5. Run the 'sm64.py' script

## Additional Libraries Used
- https://github.com/tartley/colorama
- https://github.com/wong2/pick
- https://github.com/joeyespo/py-getch

# Anti-AFK
A python script that detects when your mouse has moved, and moves your mouse a little bit if it has not moved for over 10 seconds (prevents AFK kick on many games).
# How it works
Anti-AFK uses the Python library [pynput](https://pypi.org/project/pynput/) for mouse movement and detection.  Also, [wxPython](https://wxpython.org/) is used for the GUI.

To install the required libraries, make sure you have python installed first, then open CMD/Terminal and run:

    pip install pynput
    pip install -U wxPython

Then run the python script to use the program.

If you would prefer to have this program as a standalone executable, I would recommend you use [PyInstaller](https://pypi.org/project/pyinstaller/)

## License
[MIT](https://choosealicense.com/licenses/mit/)

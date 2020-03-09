# Simple_Calculator_App
Build your first python software and package it into a standalone executable file

## Intructions using PyCharm
1. Create a simple GUI
  - Use the Tkinker toolbox
  - Build buttons and labels
2. Link commands to buttons
3. Process operations and user input
4. Integrate error message box for error handling
  -Use tkMessageBox.showwarning
5. Create an executable (.exe) file 
  -Install Pyinstaller (Windows instructions)
    A) Left click in script > Click open in terminal > type: pip install pyinstaller (This installs pysintaller - see www.pyinstaller.org)
    B) In the same directory type: pyinstaller scriptname.py (This generates a bundle called *dist*. This creates a folder that has the exectuable part of the script that you will want to provide to the user.) 
    C) In the terminal type: 
      1) pyinstaller --noconsole scriptname.py (This gets rid of the console window
      2) pyinstaller.exe --onefile --windowed --name appname --icon ==youriconame.ico scriptname.py (You need an ico for this step. You can generate one using a png to ico converter- This step generates a windows icon for your .exe file)
    

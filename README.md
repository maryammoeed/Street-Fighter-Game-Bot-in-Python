# Street-Fighter-Game-Bot-in-Python

Welcome to the README guide for the GameBot tournament! This document contains detailed instructions on how to set up and run the provided code solution for the tournament game. Follow the steps below to install the necessary dependencies and execute the code successfully on your machine.


Prerequisites and Dependencies:
Before proceeding with the installation, ensure that your system meets the following requirements:

* Operating System: Windows 7 or above (64-bit)
* Python version 3.6.3 or higher (Note: The code has been tested on version 3.6.3 but should work on higher versions. Minor modifications may be required for versions below 3.)
* Prerequisites for the BizHawk emulator.

Installation and Setup:
To install and set up the GameBot environment, follow these steps:

1. Extract the contents of the attached zip file to your preferred location on your machine.
2. Install Python 3.6.3 or a higher version if it's not already installed. You can download Python from the official website (https://www.python.org/downloads/).
3. Install the numpy library for the game by running the following 
command in the command prompt or terminal:
pip install numpy

4. Once the dependencies are installed, choose the appropriate folder based on your requirement:
* For running a single bot (your bot vs CPU), open the "single-player" folder.
* For running two of your bots simultaneously (both fighting each other), open the "two-players" folder.

Running the Game and Executing the API Code:
1. To run the game and execute the API code, follow these steps:
2. Open the "EmuHawk.exe" file located in the BizHawk emulator folder.
3. From the emulator's "File" drop-down menu, choose "Open ROM" or use the shortcut "Ctrl+O".
4. Browse to the respective folder (single-player or two-players) and select the "Street Fighter II Turbo (U).smc" file.
5. From the emulator's "Tools" drop-down menu, open the "Tool Box" or use the shortcut "Shift+T".
6. Leave the emulator window and the tool box open. Then, open the command prompt or terminal and navigate to the directory where the API code is located.
7. Run the following command in the command prompt or terminal to execute the Python API code: python controller.py 1
8. Note: The '1' at the end of the command is a command-line argument. Use '1' to control player 1 (left-hand side player in the game) through your bot. If you want to control player 2 (right-hand side player in the game), use '2' as the command-line argument. Any other command-line argument will result in an error.
9. After executing the code, go to the emulator window and select your character(s) in the game after choosing the normal mode. You can configure the controls for selecting players from the "Controllers" option in the "Config" drop-down menu of the emulator.
10. In the emulator, click on the second icon in the top row (Gyroscope Bot). This action establishes a connection between the emulator and the API program. You should see the message "Connected to the game!" or "CONNECTED SUCCESSFULLY" in the terminal or command prompt.
11. If you have successfully completed all the steps above, you have now run the GameBot starter code successfully.
12. The program will stop once a single round is finished. To run the emulator and the code again, repeat the process from Step 1.
13. To run two bots at the same



# Music Player in Python
This program is a simple music player that uses the Pygame and Tkinter libraries to play and control music files. It allows the user to select songs from a list and perform basic operations such as playing, pausing, stopping, and resuming.

# Requirements
Python 3.x,Pygame,Tkinter,mixer.

# Usage
Install Python 3.x and the Pygame and mixer,Tkinter libraries.
Download or clone this repository to your local machine.
Open the terminal and navigate to the directory where the repository is located.
Run the following command to start the music player:
python musicplayer_2.py
Select a song from the list by clicking on it.
Use the buttons to control the playback of the selected song.

# Functions
playsong(): Loads and plays the selected song.
pausesong(): Pauses the currently playing song.
stopsong(): Stops the currently playing song.
resumesong(): Resumes the playback of the paused song.

# GUI Buttons
Play: Starts playing the selected song.
Pause: Pauses the playback of the selected song.
Stop: Stops the playback of the selected song.
Resume: Resumes the playback of the paused song.

# Algorithm
This code is a simple music player that allows the user to select a song from a playlist and play, pause, resume, or stop it using buttons. Here's the algorithm for this code:
step1:Import necessary libraries: pygame, tkinter, and os.
step2:Define the functions for playing, pausing, stopping, and resuming the selected song. Each function uses the mixer module from pygame to control the music playback.
step3:Create a tkinter window and initialize the mixer.
step4:Create a Listbox widget to display the playlist of songs. Set the selectmode to SINGLE so that only one song can be selected at a time. Set the background color to black, foreground color to white, and font to 'optima' with a size of 15. Set the width and height of the widget to 32 and 7, respectively. Grid the widget to the root window with columnspan=20.
step6:Change the current directory to the directory containing the music files.
step7:Get a list of all the songs in the directory using the listdir function from os module.
step8:Insert each song in the playlist widget using a for loop.
step9:Create buttons for playing, pausing, stopping, and resuming the music playback. Configure each button with a font of 'candara' and a size of 20. Set the background and foreground colors and padding for each button accordingly. Grid each button to the root window with appropriate row and column numbers.
step10:Start the mainloop to run the tkinter window.
That's it! The user can now select a song from the playlist and control the music playback using the buttons.

# Credits:
This Music Player project is developed by Venata Praneeth Yarrapathruni

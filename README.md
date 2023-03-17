# Text_To_Speech
This is a Python code for a GUI application that converts text to speech using the pyttsx3 library.
The code imports the required modules including tkinter, pyttsx3, and os.
The code creates a Tkinter window using Tk() function and sets the window's properties, such as the title, size, and background color.
The code initializes the text-to-speech engine using the pyttsx3.init() function.
The code defines a function called speak() that converts the text entered by the user in the text area to speech using the say() and runAndWait() methods of the text-to-speech engine. 
The function also sets the voice and speed of the speech based on the user's selection from the gender and speed dropdown menus.
The code defines another function called download() that allows the user to download the speech as an MP3 file.
The code creates a top frame for the window that contains the application logo and title.
The code creates a text area where the user can enter the text to be converted to speech.
The code creates two dropdown menus for selecting the gender and speed of the speech.
The code creates two buttons: one for converting the text to speech and the other for downloading the speech as an MP3 file.
The code runs the Tkinter main loop using the mainloop() function.
Overall, this code provides a simple and user-friendly interface for converting text to speech using Python.

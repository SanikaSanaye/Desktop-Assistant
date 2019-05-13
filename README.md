# Desktop-Assistant
Desktop assistant using Text-To-Speech to perform various tasks using voice activation.


Algorithm Used

•	The commands from user are recognized using Speech Recognition. 
We are using the default API key for Google Speech Recognition to recognize speech spoken by the user.

•	A list of operations is provided with respect to the spoken speech.
Using regular expressions, we extract information and match it with provided list of operations. 
Regular expression is a sequence of characters that define a search pattern.
Usually this pattern is used by string searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

•	The operation once matched will execute the code defined in it. 
The webbrowser module is used for opening a folder, to open any website and to display the current weather in a particular city in India. 
The selenium package is used to automate web browser interaction from Python.
To make or remove a folder the os.mkdir or os.rmdir functions of the os module are used.
The vlc module is used to play or stop music. The program is termintated using sys.exit function of exitstatus module.

•	The output is given by the desktop assistant in text as well as speech medium using Text-To-Speech(TTS) methods provided by pyttsx3 module. 
The assistant continues to excute until it is commanded to terminate.

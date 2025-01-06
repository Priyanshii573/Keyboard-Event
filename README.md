# Keyboard Event Tracker 

# Description:
This project demonstrates the use of keyboard events in a web page, capturing details about the keys pressed in a search bar. When a user types a character, the project displays the following information:
The key pressed.
The key code (event.keyCode).
The character code (event.charCode).
The type of the event (keydown, keypress, keyup).

The goal of this project is to show how JavaScript can capture and display dynamic keyboard event data, making it a useful tool for understanding how key events work in web development.

Key Features:
HTML for creating the search bar and displaying the captured event information.
CSS for styling the page and making it visually appealing.
JavaScript for handling and displaying keyboard events when typing into the search bar.

# How It Works:
As a user types a character in the search bar, JavaScript listens for keyboard events (keydown, keypress, keyup).
For each key press, the JavaScript code retrieves and displays:
key — the character of the key pressed.
keyCode — the numerical code corresponding to the key pressed.
charCode — the character code for the key pressed.
event type — the type of keyboard event triggered (e.g., keydown, keyup).
This information is displayed live on the screen as the user types.

# Installation:
Clone the repository.
Open the keyboardevent.html file in your browser.
Start typing in the search bar to see the details of the keyboard events.

# Technologies Used:
HTML5
CSS3
JavaScript (for handling keyboard events and displaying data)
Example:

If you type the letter "A" in the search bar:
Key pressed: A
Key code: KeyA
Char code: 65
Event type: keyup

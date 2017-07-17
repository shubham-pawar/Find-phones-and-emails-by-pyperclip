Find numbers and Emails by pyperclip

Requirements:-
pip install the following package:-
pyperclip

About pyperclip :-

The purpose of Pyperclip is to provide a cross-platform Python module for copying and pasting text to the clipboard.

To copy text to the clipboard, pass a string to pyperclip.copy(). To paste the text from the clipboard, call pyperclip.paste() and the text will be returned as a string value.

            import pyperclip
            pyperclip.copy(‘Hello world!’)
            pyperclip.paste()
            ‘Hello world!’

Steps to implementation :-

    1)Download a zip file and unzip it.
    2)First copy any phone numbers of the format (E.g. 123-545-1818) and Email IDs of the format (E.g. shubhampawar1234@gmail.com)
    3)Open the Terminal and go to the directory where your file is saved (Using the ~/cd repo-name)
    4)Run the phoneAndEmail.py file by following command
    python phoneAndEmail.py + hit the Enter key.
    5)The phone numbers and Email IDs will displayed on the terminal screen.

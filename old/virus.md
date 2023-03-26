# Python Viruses

### [Repository](https://github.com/ChandlerJayCalkins/UIdahoCS336VirusPresentation){:target="_blank" rel="noopener"}

- Demo viruses for Windows that infect other python files
- Made in fall 2021 for a presentation in Introduction to Information Assurance class to demonstrate viruses
- All viruses were made by me in about a week
- Virus 1 infects python files with a comment just to show how to infect files
- Virus 2 infects python files with actual code that makes the victim's keyboard unusable
	- Infected file creates a script in the Windows startup directory and runs it
	- The script turns capslock, numlock, and scroll lock on and off repeatedly so lights flash on and off on the victim's keyboard
	- The script also spams the string "lol " over and over again through the keyboard so the victim can't type anything
- Virus 3 does the same thing as virus 2 except it's polymorphic
	- This means that the payload that the virus infects files with is different every time
	- This makes it much harder for anti-virus software to detect files infected by this virus
- The discord virus infects discord bots and makes them kick everyone from a server and delete all of the channels when they start up
- Professor offered to hire me for a research opporunity because of the presentation

# Logfile Entry script

A general purpose Home Assistant YAML script for writing entries into a log file with a customised format. 

It is used in several of my blueprints and includes the possibility not to write a log at all by providing a blank notification service name. 
This does however mean that the script must be there even if no logfile is required.  

# Installation 

I recommend you install this script as a **package** 
1. If you do not already have packages, follow [these instructions](https://www.home-assistant.io/docs/configuration/packages/)
2. In your package folder create a file called (something like) *logfile_entry.yaml*
3. Copy the contents of the script into that file
4. Restart the system or reload all YAML   


---
If you find any of the ideas in this repository useful, please [Buy Me a Coffee](https://buymeacoffee.com/andysymons)

# MAKE LOBBIES GREAT AGAIN - STRIKE EDITION
## HOW DOES IT WORK?
MakeLobbiesGreatAgain uses a packet capture library to detect STUN packets from the client and server of Dead By Daylight, in order to determine who you're connected to and get ping from.
It is not detected as a hack, since it does not and will not interact with the game ever. 


## APPLICATION SUPPORTS BOTH KILLER AND SURVIVOR

**NOTE**: If you were linked here from another source, such as Reddit, be sure to check for the latest versions for the best quality. You can find all my versions here: [MLGA Releases](https://github.com/Frubi22/MakeLobbiesGreatAgain/releases)

MLGA from other devs: [MLGA Forks](https://github.com/Frubi22/MakeLobbiesGreatAgain/network)

Primary Feature:
* Determining Ping

Optional Features: 
* Double-Click to lock/unlock the overlay for dragging
* Shift + Left Click on a player, highlighted in a darker color for current selection, to toggle to 1 STRIKE, 2 STRIKES, BLOCKED, LOVED, or back to the normal display
* To exit, simply look for Jake's face in your system tray near the clock, right-click, and select Exit.

## HOW TO INSTALL AND USE:
**System Requirements:**
* Latest Java Runtime https://java.com/en/download/
* Npcap from https://nmap.org/npcap/ and tick "Install Npcap in WinPcap API-compatible Mode" during installation (For advanced users: Add %SystemRoot%\System32\Npcap\ to PATH instead.)
* Download MLGA here: [MLGA Forks](https://github.com/Frubi22/MakeLobbiesGreatAgain/network)

Simply double double click on the MLGA.jar file to run

**NOTE:** You may need to right-click the JAR file, select Properties, and choose Unblock if it appears below Attributes.

**If UAC is enabled:** 
You may need to run the application via Command Prompt (this is due to the PCap4J library being unable to find devices).
* Copy the folder path that MLGA is in, for example: C:\Users\Dwight\Desktop\MLGA\
* Right-click in the same directory as MLGA and create a new text document
* Open it with Notepad and type, cd C:\The\Path\You\Copied\Earlier
* Start a new line with Enter and type, javaw -jar MLGA.jar
* Choose Save As and name it MLGA.bat with the option All Files selected
* Right-click the new batch file and Run as Administrator

## HOW TO SUBMIT A DEBUG LOG
* Right-click in the same directory as MLGA and create a new text document
* Open it with Notepad and type, java -jar MLGA.jar
* Choose Save As and name it MLGADebug.bat with the option All Files selected
* Right-click the new batch file and Run as Administrator
* Submit a picture or copy of the text to an Issue

# Cold Call System
## Install Instructions
1. Clone Cold Call System: `git clone https://github.com/JaegerJochimsen/ColdCallAssist.git`
## Operation Instructions
### Initial Setup
Create a roster file containing student information. 
**Roster Requirements:**
1. The roster must be a text file (.txt) with each line holding a single student's information.
2. Each line will be tab-delimited and contain the following student information:
*<First Name><tab><Last Name><tab><ID Number><tab><Email Address>(optional)<tab><Phonetic Spalling>*
(see User Documentation/Manual for more)
### Starting the System for the First Time
1. From terminal navigate to ColdCallAssist directory.
2. Execute the program `python3 ColdCall.py`.
3. Select an initial roster via the file navigation window.
4. Confirm the roster.
5. The top bar should populate with student names; if this is the
   case the system is up and running.
### Subsequent System Usage (Same Roster)
1. From terminal navigate to ColdCallAssist directory.
2. Execute the program `python3 ColdCall.py`.
### Subsequent System Usage (Modified Roster)
The Cold Call Assist system supports the addition of new students to the initial roster, but not removal (see What's Next below). 
### Subsequent System Usage (Using a New Roster)
Reset the system in order to upload a new student roster.
### System Controls
| Keystroke       | Description    |
|-----------------|----------------|
| Right Arrow Key | Navigate Right |
| Left Arrow Key  | Navigate Left  |
| Comma Key ,   | Mark Student Contribution |
| Period Key . | Flag Student |
| Question Mark Key ? | Mark Student Absent |
|-----------------|----------------|
Close the interface window to exit the program.
### Resetting the System
Dependencies
file manifest
list of known bugs
troubleshooting instructions
credits
## What's Next

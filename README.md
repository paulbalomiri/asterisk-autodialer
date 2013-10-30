# asterisk-autodialler

This project aims at creating a simple dialler with functionality for

* Detecting Voicemail
* Offering different choices for the user
* Reacting in-call to those choices
* Submitting the choice after the call has been made
* Implementing retry strategy


# Diagram
The diagram below illustrated the flow of a call or call attempt.
Rectangles represent Actions, while rhombi represent choices.

Green Rectangles are playback Actions for which Recordings must be supplied

![diagram](/doc/flowchart.png?raw=true)

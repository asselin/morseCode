Notes

3 buttons
3 event handlers
event handler for keyboard

constant
mapFromMorseCodeToLetters

variables
translatedMessage
currentMorseCode

Initialization
	Setup variables
	Setup event handlers

Event handler for dot/dash
	Add the dot/dash to currentMorseCode
	Check what are the possible letters for the morse code entered so far
	Update the display with the currentMorseCode & the possibilities

Event handler for space
	Check if there's a valid letter
	if YES
		Add the letter to the translatedMessage
	If NO
		Add ? to translatedMessage
	Clear currentMorseCode and possible letters

Function
	getPossibleLetters(currentMorseCode) -> Array of possible translations


# hackmerlinsolver
AI Agent to solve HackMerlin

Overall Pipeline:
Used playwright to interface with the website
Template inputs fed into HackMerlin
The program takes output from HackMerlin
The program feeds that output into an AI (relatively dumb AI used here because of cost)
The AI analyzes the input and gives back either the password or NONE
The program chooses whether to continue with questions or respond with password
Loops through this procedure

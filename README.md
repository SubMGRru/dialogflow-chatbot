# dialogflow-chatbot
The simplest live chat bot example I could make. 
It employs Dialogflow (which is free) and takes about 10 minutes to setup.

<b>STEPS</b>
1. Create Dialogflow account.
2. Create new agent.  [CREATE AGENT]
3. Name the agent, and click [create].
4. Add an "Intent" by clicking [CREATE INTENT].
5. Name the "Intent". This is the start of how user input will be routed to a proper respone.
6. [Add training phrases] which are expected user input mine:
      ex1: green idea for the day
      ex2: daily eco advice
      ex3: tip to save planet
7. [Add Response] which is how the bot should respond to training phases:
      ex1: eat less red meat
      ex2: open windows and turn of heating/cooling
      ex3: turn off lights
8. Click [Save], and wait for AI to train on the new data
9. Navitgate to [Integrations]
10. Activate "web demo" option. and a popover should apear, if not click "web demo".
11. Copy the code shown, and paste it anywhere in body index.html file.
12. create a "gh-page" branch to the repository, 
13. Set to default branch in repository settings, and scroll down to new link.

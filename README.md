# Chatbot-using-Dialogflow
In this project I have implemented chatbot using Dialogflow platform. For database connectivity I  have used Google Spreadsheet and converted as an APIs. For the fulfillment part I have deployed in Telegram Application.

Steps to follow:
1) Login to Dialogflow 
2) Create Agent name
3) Now go intent section for making questionnaire
4) for intent :
1) click on create new intent
2) Give name to your intent
3) In the Traning phrase write different numbers of question you want to train.
4) If you want to add default responses then go to reponse section and add some response.
5) Or else if you want to connect your response to API or Database Then scroll down and go to fulfillment section and enable  "Enable webhook call for this intent".
6) Then save it.


1) For connecting Dialogflow to Telegram:
2) Login to Telegram and go to https://telegram.me/botfather
3) Click the Start button in the web interface or type /start
4) Click on or type /newbot and enter a name
5) Enter a username for the bot, ending in "bot" (e.g. garthsweatherbot)
6) Copy the generated access token
7) In Dialogflow, go to Integrations in the left hand menu
8) Click on the Telegram tile
9) Paste the Access Token into the related field
10) Click the Start button


1) For fulfillemt part I have given the code.

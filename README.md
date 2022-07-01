# Self-disclosure Chatbot Dataset
The dialog data can be found in the `dialog.csv` file.
(The survey results will be updated soon.)

* `timestamp`: the time of each dialog turn
* `user_id`: user id
* `topic`: The topic being discussed (`MOVIECHAT` or `COVIDCHAT`)
* `last_bot_text`: The response from chatbot at the last dialog turn
* `user_text`: The response from the user at the current dialog turn
* `bot_text`: The response from the chatbot at the current dialog turn
* `group`: The experimental group (`FD`: factual-disclosure group, `CD`: cognitive-disclosure group, `ED`: emotional-disclosure group, `AD`: adaptive-emotional group)
* `user_self_disclosure_level`: the detected self-disclosure level from the user response.

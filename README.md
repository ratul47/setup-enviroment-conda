# setup-enviroment-conda
## CMD lines:-->

- conda create --name installingrasa python==3.7.6 [For installing in anaconda
- conda activate installingrasa
- conda deactivate
- conda install ujson
- conda install tensorflow
- pip install rasa
- rasa init
- rasa shell 
- rasa train
- rasa run  --enable-api
- rasa run --enable-api --cors “*”
- rasa run -m models --enable-api --cors “*”

##  credentials.yml onfigaration
socketio:
  user_message_evt: user_uttered
  bot_message_evt: bot_uttered
  session_persistence: true

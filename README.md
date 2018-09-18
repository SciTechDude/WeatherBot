## WeatherBot ( using older Rasa NLU and RASA Core)

A text chatbot based on Rasa NLU and RASA Core that interacts with user and gives real-time weather information via https://www.apixu.com/ API.

#How to use this Repo

Install dependancies as per `requirement.txt`

``` pip -r requirement.txt ```

Train and test the NLU models
``` python nlu_model.py ```

Train and test the Rasa Core model
``` ``` python train_online.py ``` 

Final Dialogue with the chatbot

``` python3 dialogue_management_model.py ```

# Status
In progress


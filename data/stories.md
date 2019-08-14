## restaurant path
* greet	
  - utter_greet

* mood_great
  - utter_happy

* restaurant_search
  - utter_ask_location
  
* got_location
  - utter_ask_cuisine
  
* got_cuisine
  - utter_affirm
  - utter_show_restaurants

* goodbye
  -utter_goodbye

## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
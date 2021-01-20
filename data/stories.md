## happy path
* mood_great
  - utter_happy

## facebook
* facebook
  - utter_facebook

## gmail
* gmail
  - utter_gmail

## sad path 1
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## New Story
* greet
    - utter_iamabot

## Booking story
* GET_BOOKING_INFO
    - utter_sure_help
* BOOKING_ID
    - utter_thanks

## New Story

* facebook
    - action_default_ask_rephrase

## New Story

* gmail
    - utter_gmail
* facebook
    - utter_facebook

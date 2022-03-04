# Node-RED flow using Alexa notifications of Wallbox status

This node-red flow uses Home Assistant to integrate the Wallbox charger API with Alexa. Node-RED is used to poll the Wallbox API and send any change in status (including offline or general comms failure) to Alexa as a notification to be spoken.

Home Assistant needs the Wallbox integration alongside the HACS "Alexa Media Player" community integration. Node-RED needs node-red-contrib-home-assistant-websock installed.

Update the json or the service nodes' Service field with your Alexa device(s) name(s).

# Esphome-solutions
Ever-expanding collection of esphome solutions.
Feel free to use these, but use at your own risk. I am not responsible for any issue caused.

# Available solutions
|Solutions|files
|---|---|
|Battery powered version of Baby buddy panel built using ESP32 [More info here](https://github.com/jeroenterheerdt/Baby-Buddy-Keypad)|[babybuddy-panel-battery.yaml](babybuddy-panel-battery.yaml)||
|USB powered version of Baby buddy panel built using ESP32. [More info here](https://github.com/jeroenterheerdt/Baby-Buddy-Keypad)|[babybuddy-panel.yaml](babybuddy-panel.yaml)|
|Shelly-compatible smart light switches|[backdoorlight2.yaml](backdoorlight2.yaml), [frontoutdoorlights2.yaml](frontoutdoorlights2.yaml), [hallwaymini1.yaml](hallwaymini1.yaml), [livingroommini1.yaml](livingroommini1.yaml), [livingroommini2.yaml](livingroommini2.yaml), [livingroommini3.yaml](livingroommini3.yaml), [smartlightswitch1.yaml](smartlightswitch1.yaml)|
|ESP8266-based garage doors controller for 2 doors (easily expandable to more). Uses relays (one per door, but can be adapted) and ultrasound distance sensors. Includes switch to lock doors and vehicle presence detection.|[garagedoorscontroller.yaml](garagedoorscontroller.yaml)|
|ESP8266-based grill / smoker thermometer with thermocouple and DSM501A smoke sensor|[grillthermometer.yaml](grillthermometer.yaml)|
|Shelly-compatible smart fan switch|[guestbathroomfan2.yaml](guestbathroomfan2.yaml), [masterbathroomfan.yaml](masterbathroomfan.yaml)|
|Presence detection using Tile and ESP32|[hallway.yaml](hallway.yaml), [kitchen.yaml](kitchen.yaml), [tvroom.yaml](tvroom.yaml)|
|Hottub controller: ESP32-based Temperature sensor, pH sensor and two solenoid to remotely measure and change hottub temperature (solenoids actually press up/down physical buttons). Also includes presence detection using Tile.|[hottubcontroller.yaml](hottubcontroller.yaml)|
|Sonoff basic compatible switch|[irrigation1.yaml](irrigation1.yaml), [outdoor-lights-box-1.yaml](outdoor-lights-box-1.yaml)|
|M5stack Atom Echo - doesn't do anything yet|[m5stack-atom-echo-a27b70.yaml](m5stack-atom-echo-a27b70.yaml)|
|ESP32-based controller for electric heater, uses IR signals to mimic the remote. Also includes presence detection using Tile.|[office.yaml](office.yaml)|
|ESP8266-based controller for outdoor holiday lights, includes mimicing a IR remote|[outdoor-lights-box-2.yaml](outdoor-lights-box-2.yaml)|
|ESP8266-based controller for proofing box. Controls a heating mat using a relay to maintain a set temperature.|[proofercontroller.yaml](proofercontroller.yaml)|
|ESP32-based mailbox sensor, leverages a reed sensor and a magnet. If magnet is close to sensor the mailbox is reported as closed and the ESP32 is in deepsleep. It wakes up when the magnet is removed (mailbox is open) and then sleeps after a couple of seconds. Is battery powered (2x AA) so uses MQTT instead of native API to connect to HA.|[mailbox.yaml](mailbox.yaml)|

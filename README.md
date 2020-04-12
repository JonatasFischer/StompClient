# StompClient
A STOMP client library for use with Arduino ESP8266 and Websockets

# Description
Small library to allow devices which can run the ArduinoWebsockets library (https://github.com/gilmaimon/ArduinoWebsockets.git) to 
connect to a STOMP broker, either directly or using SockJS wrapper.

# Examples
There are two example sketches included, which should be used together.

The examples have been tested using the https://github.com/dmcintyre-pivotal/ESPStompExample application, which is a simple Stomp server implemented using Spring Boot.


# Fork Observations
This is a Fork of the original project in order to change the WebSocket library and make it work with SockJS and normal 
WebSokects.
In order to use SockJS version just define USE_SOCK_JS before including the library
Ex:
#define USE_SOCK_JS  
#include "StompClient.h"


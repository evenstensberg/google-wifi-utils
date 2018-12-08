# google-wifi-utils
Information on how to obtain telemetry from google wifi

## Introduction

I bought myself a Google Wifi to check if I can get diagnostic data from it to make an app that outputs the information in a different way. Turns out most of the routes exposed internally at your network is rubbish.


## Prereqs

This assumes that you know infosec and web development. This is because we would need to find out the token associated with your google wifi client as well as the oauth token that you will need to make requests to the service Google fetches data from. 

Luckily, Google follows strict convention, so it would make our job easier :)

## Routes

- https://autopush-accesspoints.sandbox.googleapis.com/
- http://192.168.86.1/ (Your local wifi address)
- https://people-pa.googleapis.com
- http://googleapis.com


## Relative Links

- https://github.com/marcosscriven/galeforce
- https://gist.github.com/Zenexer/e1c03b87fee6236c71e4fefcb1ff73a9

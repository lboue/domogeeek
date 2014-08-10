DomoGeeek
=========

Domotic apps experiments based on Z-wave / Raspberry / NodeJS / MongoDB.
These apps are totally experimental for the moment.

## GroupSMS
The Group SMS app allows persons to subscribe to group SMS. 
When a message is sent to this list, the message is sent also to all the subscribers of the list.
Useful to connect all your neighbours throw an SMS Mailing list.

## ZwaveBus
The ZwaveBus app allows to manage your Zwave devices. All the events received are transmit to a bus.
You can quickly develop your own listeners that respond automatically to Z-Wave events.
All changed value events are stored into MongoDB.

## Multipush
The Multipush app allows to broadcast a message on multiple canal : sms, mail, karotz, openkarotz ...
Multipush exposes a REST service easy to use to send a message quickly to any device.

## Scheduler
The Scheduler app provides a tasks mechanism to schedule tasks like opening or closing the shutters automatically when your are in travel.
This app is based on the cron module from NodeJS.

----
### Directory description

* apps : Contains Node.js apps.
* deps : Contains specific Node.js modules that need to be installed (npm install xxxx -g)
* lib  : Contains shared libraries for the apps.
* misc : Contains miscellaneous code.
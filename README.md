# EstimoteBeacons Beacons widget

## Prerequisites

This module and widget requires estimote beacons to work with. These can be bought online here:

https://order.estimote.com/buy/proximity-devkit

The module requires the push notifications module in order to send notifications to the user that they are near a estimote beacon.


## Setup

1. Add the widget which can be found in the dist folder to the widget folder.
2. Add the module to your project.
3. Add the pages Beacons and Notifications Admin to the navigation.
4. Add your beacon ID's and Minor and Major numbers to the widget.
5. Add the Beacons startup microflow to your microflow startup flow.
7. Run the app.
6. Add your beacons and notification triggers in the admin section.
7. Include in your config.xml the plugin bellow:
```xml
    <plugin spec="https://github.com/vertica-as/phonegap-estimotebeacons" source="git" />
```
Finally Build your phonegap app using phonegap build.

### Beacon Information
Beacons available:

```txt
Ice = Lightblue
Mint = Lightgreen
Blueberry = Purple

UUID is a standard one: B9407F30-F5F8-466E-AFF9-25556B57FE6D, you do not have to change it

Major - Minor   (color)
----------------------------------------
13359 - 49963   (ice)
30134 - 29958   (mint)
22501 - 49963   (blueberry)

21284 - 27303   (blueberry)
28248 - 42873   (ice)           Location: Coffee factory
44889 - 16895   (mint)

17235 - 37898   (ice)           Location: Mainstage
62382 - 11633   (blueberry)     Location: Mainstage
47240 - 17392   (mint)          Location: Expo theater

2665  - 25829   (ice)           Location: Tea room
39577 - 33944   (mint)          Location: Mainstage
47108 - 26430   (blueberry)     Location: Tea room

15610 - 11661   (ice)           Location: Hackathon 1 (Virginia)
21872 - 49517   (blueberry)     Location: Hackathon 2 (Arabica)
13052 - 13249   (mint)          Location: Entrance (Registration)

18629 - 4392    (ice)           Location: Mendix Booth
46041 - 59981   (blueberry)     Location: Tea room
41434 - 12201   (mint)          Location: Tea room
```
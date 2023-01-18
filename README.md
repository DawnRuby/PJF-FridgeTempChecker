CHANGELOG:
==================================================
Additions:
- Added Wiring Diagrams
- Fixed Folder Structure to be a bit better


BEFORE YOU START:
==================================================
There are a few Requirements for this to work.
First off you need special a Temperature Controller for the whole project to work.
I'm currently using DHT22 AM2302 but any Digital Temperature sensor will work.
I'm using a NodeESP in this example but this is very overkill. The Cheapest and worst Arduino will do except you want to add some
smart functionality to this example.
You also need a little speaker. I'm using a higher quality speaker here I had lying around but depending on how far away the fridge is a simple piezo maybe enough.

Note that the Wiring diagram is provided AS IS and will probably not change much anymore. I may add this to a hub that I'm planning to work on to see if your fridge needs defrosting however (this is why this is using a humidity / temperature sensor too)

This is the wiring diagram and board design currently used for Prototyping:

![**WiringDiagram**](https://i.imgur.com/2DzZ5vt.png)
![**BoardSCM**](https://i.imgur.com/uAVSCdW.png)


 About Commits:
==================================================
Dailys (even though they do not occur daily) fix small bugs and usually took only a few minutes to develop. So more or less they fix stuff that wasn't really a issue or implement libary updates. They do **NOT** Feature Major changes or Bugfixes for anything noted. Daily updates are __**NOT**__ recommended in production usage, I recommend using a commit from the Release site.
